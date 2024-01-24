# Compose article
The Learn Together app displays a list of articles about several Jetpack libraries. Users can choose the topic of their choice and learn about its latest developments.

In this exercise, you build a screen for the app, which displays a tutorial for Jetpack Compose. You use the image and string resources provided in the Resources section for this problem.

# Final screenshot
After you finish the implementation, your design should match this screenshot:
<img width="293" alt="Screenshot 2024-01-23 at 01 26 29" src="https://github.com/Hitendra27/ComposeArticle/assets/73651340/99cc6e14-0e55-4c4c-a8e6-a7f47ae1e8ab">

# UI specifications
Follow this UI specification:
<img width="694" alt="Screenshot 2024-01-23 at 01 27 56" src="https://github.com/Hitendra27/ComposeArticle/assets/73651340/f03cce17-bccd-4b9b-b997-a50049952879">

UI specification for building the Compose article screen.

1. Set the image to fill the entire screen's width.
2. Set the first Text composable to a 24sp font size and 16dp padding (start, end, bottom, and top).
3. Set the second Text composable to a default font size, 16dp padding(start and end), and Justify text align.
4. Set the third Text composable to a default font size, 16dp padding (start, end, bottom, and top), and Justify text align.
   
# Resources
You need this image to import into your project and these strings:

* Jetpack Compose tutorial
* Jetpack Compose is a modern toolkit for building native Android UI. Compose simplifies and accelerates UI development on Android with less code, powerful tools, and intuitive Kotlin APIs.
* In this tutorial, you build a simple UI component with declarative functions. You call Compose functions to say what elements you want and the Compose compiler does the rest. Compose is built around Composable functions. These functions let you define your app\'s UI programmatically because they let you describe how it should look and provide data dependencies, rather than focus on the process of the UI\'s construction, such as initializing an element and then attaching it to a parent. To create a Composable function, you add the @Composable annotation to the function name.

Hint: Which composable aligns its children vertically?

References
TextAlign.Justify property
