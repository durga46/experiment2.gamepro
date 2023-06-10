# Ex No :02

# <p align="center"> Create a player movement using pawn,collectable,player health and score l</p>

## AIM:
TO Create a player movement using pawn,collectable,player health and score.

## STEPS REQUIRED:To create and destroy the coin:
Create a new project in Unreal Engine and choose a template that suits your needs.

Add a new actor to the level and call it "Coin".

Create a new blueprint based on the Coin actor by selecting it in the Content Browser and choosing "Create Blueprint".

Open the Coin blueprint and add a static mesh component to represent the coin. You can import a 3D model or use one of the default shapes provided by Unreal Engine.

Add a collision component to the Coin blueprint so that the player can interact with it. Choose a simple collision shape like a sphere or a box.

Add a variable to the Coin blueprint to keep track of whether the coin has been collected or not. Call it "IsCollected" and set its default value to false.

Create a new blueprint based on the player character by selecting it in the Content Browser and choosing "Create Blueprint".

Open the player blueprint and add a collision component to represent the player's interaction with the coins.

Add an event to the player blueprint that gets triggered when the player collides with a coin. Use a collision event and check if the collided actor is a coin.

If the collided actor is a coin, check if it has already been collected. If not, set its IsCollected variable to true and add its value to a score variable in the player blueprint.

Remove the coin from the level by calling its Destroy function.

Add several instances of the Coin actor to the level and adjusttheir positions so that they are spread out and not too close to each other.

## OUTPUT:

### Starting position of the player:
![image](https://github.com/durga46/experiment2.gamepro/assets/75235704/2ba49e0e-c0c8-4284-89bf-c8cb56e8c694)

## PROCEDURE:

### To redirect to levels:

Create a new level or open an existing one.

Add a new widget blueprint by going to the Content Browser and right-clicking in the desired folder. Select User Interface and then Widget Blueprint.

Design your menu by adding buttons and other UI elements to the widget. You can use images, text, and other widgets to create a visually appealing menu.

Add a button to your menu by dragging and dropping a Button widget from the Palette onto your canvas.

In the Button's properties, scroll down to the On Click section and click the + button next to the On Click event.

Create a new custom event by clicking the New Binding button and selecting Custom Event.

Name the custom event "LoadScene" or something similar.

Open the Level Blueprint by going to the Blueprint menu and selecting Open Level Blueprint.

Drag and drop your menu widget from the Content Browser into the Level Blueprint.

Create a new variable in the Level Blueprint by clicking the Add Variable button in the My Blueprint panel. Name the variable "MenuWidget" or something similar and set its type to the widget blueprint you created earlier.

In the Level Blueprint, drag from the MenuWidget variable and select Set to set the variable's value to the instance of the menu widget you added to the level.

Create a new function in the Level Blueprint by clicking the Add Function button in the My Blueprint panel. Name the function "LoadScene" or something similar.

Drag from the MenuWidget variable and select Get to get the instance of the menu widget.

Drag from the Get node and select Remove From Parent to remove the menu widget from the screen.

Drag from the LoadScene custom event and select Open Level to open the desired level or scene.

Connect the nodes in the LoadScene function as follows: LoadScene -> Remove From Parent -> Open Level.

Go back to your menu widget and select the button you added Earlier.

In the Button's properties, scroll down to the On Click section and select the LoadScene custom event you created earlier.

Save your changes and playtest your game. When the player clicks on the button in the menu, the menu widget will be removed and the desired level or scene will be loaded.

## CONNECTIONS:


## Play Button:
![242302850-f9abbce1-d07f-4486-a7f4-7b174e5fe11c](https://github.com/durga46/experiment2.gamepro/assets/75235704/82ef78f3-e0ca-4791-b556-48a3c8a66b94)


## Quit Button:
![242302872-d1572e81-d8ba-4e29-8927-517e30dcd69f](https://github.com/durga46/experiment2.gamepro/assets/75235704/d9444dcb-596a-4cb0-aba4-7e4561780692)


## Back Button:
![242302912-1fe733d1-d506-4d1d-a338-87dcea1f6193](https://github.com/durga46/experiment2.gamepro/assets/75235704/3d782faa-1e7e-408e-88e6-9fae4505a450)


RESULT:
Thus, To Create a player movement using pawn, collectible, player health, and score created and developed by unreal Engine.
