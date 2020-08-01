# Step By Step
## Proyecto 2
### Android

This is my documentation about the step by step of developing my project 2, version 1.

The app is developed for Android with Kotlin.

It is an app of given quotes from famous people, according the humo of the user.

### Step By Step
#### 1
Creating this document

#### 2
Creating new Android Studio project - pending

#### 3
Preparing the project: - pending

1. Deleting the View Controller from Main.storyboard
2. Re-naming the ViewController.swift to launchViewController.swift
3. Creating the extensions folder

#### 4
Adding the Navigation Controller - pending

1. Adding a new Navigation Controller at Main.storyboard
2. Deleting the Root View Controller added with the new Navigation Controller
3. Defining Navigation Controller as initial view controller
4. Adding a new View Controller, renamed as 'message'. Also linking them to the launchViewController class
5. Make a segue between the Navigation Controller and message View Controller as root view controller

#### 5
Adding launch view elements - pending

1. Adding the logo image
2. Adding the entrance label
3. Adding the start button

Adding the Extensions

1. Extension for round button
2. Extension for round label

Adding the logo Image

1. Adding the Resources folder
2. Adding the test image to Resources folder

#### 6
Adding the Colors View Controller - pending

1. Adding a new view controller
2. Change the name of view controller
3. Adding a stack
4. Adding the label and buttons at the stack
5. Adding all IBOutlets
6. Implementing the setup for label and buttons
7. Implementing an alert, maybe to explain what the app expect the user does (I don't know yet if it's necessary)
8. Implementing the IBAction for each button
9. Adding an override to go to the next view, carring the button color as background color

#### 7
Adding the Words View Controller - pending

1. Adding a new file named wordsDetailViewController
2. Implementing the variable which receive the chosen color from preview view
3. Adding a new view controller
4. Customizing the new view controller with the new class
5. Adding a stack view
6. Adding the label
7. Adding the buttons (10)
8. Adding the IBOUtlets for label and buttons
9. Setting up the buttons and label
10. Adding the IBActions for buttons
11. Adding the override to segue to the next view and bring the background color

#### 8
Adding the Message View Controller - pending

1. Adding a new view controller
2. Adding a stack, label, message view and button
3. Adding a new file named messagesViewController
4. Implementing the variable which receive the chosen color from preview view
5. Implementing the variable which receive the Title from preview view
6. Adding a new file at Resources folder, named quotes, with the variable for each word as variable and its messages as an array
7. Adding the IBOutlets for label, text view and button
8. Setting up the label, the title of message and the background of the view
9. Implementing the message text, according with the chosen word and color in past views
10. Correcting the space between the objects in the stack view
11. Impelementing the Out botton, with a segue to the Launch View.



## About The App
### Primera Pantalla

La app pregunta el color favorito del usuário, aquel día

* ¿Qué color más te gusta hoy?
* 7 colores para elegir
	* cada color es un botón

### Segunda Pantalla

La app pregunta el estado de humor del usuário, aquel día

* ¿Con qué palabra más te identificas hoy?
* 10 palabras para elegir
	* cada palabra es un botón

### Tercera Pantalla

Según las elecciones anteriores del usuário, la app le presenta una citación relacionada.

* Al elegir un color, luego una palabra - la app le muestra un mensaje
* El botón al costado derecho inferior "Salir" vuelve a la primera pantalla

### Cierre de la app

Al cerrar la app y volver a arrancarla, el proceso parte de nuevo en la *Primera Pantalla* 

## No olvidar
> *Mi trabajo no es caer bien a la gente. Mi trabajo es hacerles mejores.* Steve Jobs

### wedapp
Daniel Alves