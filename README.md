# Image Slider

This project is a React-based image slider component designed to display a series of images fetched from a specified URL. The component provides functionality for navigating through the images using arrow controls and circular indicators.

Key Features:

- Image Fetching: The component fetches images from a given URL, supporting pagination through page and limit parameters.

- State Management: It uses React's useState hook to manage the state of images, the current slide, loading status, and error handling.

- Navigation Controls: Users can navigate through images using left and right arrow buttons (BsArrowLeftCircleFill and BsArrowRightCircleFill from react-icons/bs).

- Indicator Controls: Circular indicators below the images allow direct navigation to any specific image.

- Loading and Error Handling: The component displays appropriate messages while images are loading or if an error occurs during the fetch operation.