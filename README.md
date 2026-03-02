✅ Step 1: Import Required Libraries

Imported OpenCV, NumPy, and Matplotlib for image processing and visualization.

✅ Step 2: Load Input Image

Loaded the image using OpenCV and converted it to RGB format for display.

✅ Step 3: Build Gaussian Pyramid

Created multiple levels of the Gaussian pyramid using cv2.pyrDown() to reduce image resolution step-by-step.

✅ Step 4: Build Laplacian Pyramid

Generated the Laplacian pyramid by subtracting the expanded higher-level Gaussian image from the current level using cv2.pyrUp().

✅ Step 5: Reconstruction & Visualization

Reconstructed the original image from the Laplacian pyramid and compared it with the input image to verify accuracy.

📈 Results

Successfully generated Gaussian pyramid (smoothed & reduced images).

Successfully generated Laplacian pyramid (edge/detail information).

Reconstruction matched closely with the original image.
