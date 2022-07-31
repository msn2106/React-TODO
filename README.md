# React-TODO
This is a React TODO project created for purpose of learning to apply styling to different component in a way it is easier and unique to every component.

Learned about Styling the component. There are broadly three approaches in this section.

- 1. Write raw css and use that in your components - but that has probability of spilling the UI in case it is getting applied on multiple components.

- 2. Styled Components - Used styled-components package for that - We basically have to write our styling inside the special component where all the props passed to it are available to use inside by default. This prevents same class to be applied on different components, like in above case different buttons (just in case if we want to give any specific one some special styling). It prevents it by providing the component a unique hashed class name during build time.

- 3. CSS Modules - css files are named as fileName.module.css. All the styling can be referred to a single variable while importing and that variable behaves as parent of all the classes inside the css file. Here also you can apply dynamic classes similar to raw approach. The good part here also is it provide unique class to you component, preventing you from having class name conflict in the webpage. It's class name are formatted like HTMLComponent_className_hashcode, like Button_button_xsfyL.