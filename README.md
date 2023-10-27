# MAD_Practical-9_21012011049
<b> Aim: </b> <br>
What is Frame by Frame Animation? What is Twin Animation? How can you achieve edge-to-edge content display in your app?  Create Android Application to demonstrate Frame by frame animation and splash screen to demonstrate twin animation according to below instructions.
1.	Create MainActivity according to below UI design.
2.	Create SplashActivity according to Video
3.	Create gradient Rectangle by using <gradient> tag in <shape> tag for background of SplashActivity. Use radial rectangle with x = 0.9, y =0.9, radius = 1500. Start Color pink and End Color blue. shape should be rectangle
4.	Add these all in project: <animation-list>, oneShot attribute, <set> tag, android:startOffset = 100, android:duration=1000, <scale> tag, <translate> tag, <rotate> tag, <alpha> tag <br><br>
<b> Ans: </b><br>
<b>Frame-by-frame animation:</b> Frame-by-frame animation, in the context of Android, is a traditional animation technique where a series of individual images (frames) are displayed sequentially to create the illusion of motion. Each frame represents a specific moment in the animation sequence. By showing these frames rapidly in succession, typically at a high frame rate, you create the perception of continuous movement. Frame-by-frame animation is useful for simple animations or when you need precise control over each frame's content. To implement it in Android, you can use techniques like animation drawables or programmatically changing the images in an ImageView. <br>
<br><b>Twin animation: </b> Twin animation usually refers to the simultaneous animation of two related properties or views, ensuring they move or change in sync. For example, if you want to animate both the position and opacity of an image, you can create a twin animation to ensure these changes happen together.
<br><br>To achieve edge-to-edge content display in your Android app, set system UI flags to control the visibility of the status and navigation bars, use the android:fitsSystemWindows="true" attribute in your root layout to avoid content overlap, ensure your app's interactions are compatible with edge-to-edge gestures, account for display cutouts using the DisplayCutout API, utilize flexible layout managers like ConstraintLayout, test your app on different devices and orientations, and consider device-specific configuration and resources to optimize your UI for various screen sizes and resolutions. These steps help maximize screen real estate and create a seamless and immersive user experience across a range of Android devices.
<h2>Output:</h2>
 <img src="https://github.com/mehabhatt/MAD_Practical-9_21012011049/assets/98047777/6efd150b-ac9c-40f7-a5ad-9801a99103ce" width="280" height="500">
 <img src="https://github.com/mehabhatt/MAD_Practical-9_21012011049/assets/98047777/b6671a4e-0b69-44a8-ad86-ef0f9823d67b" width="280" height="500">
 <img src="https://github.com/mehabhatt/MAD_Practical-9_21012011049/assets/98047777/b4b6c43d-f15c-4666-b0d4-58ff5b88b212" width="280" height="500">



