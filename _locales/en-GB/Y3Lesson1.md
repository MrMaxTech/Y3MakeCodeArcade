# Y3 Lesson 1- Mr Max IT

## Backgrounds and Sprites

## Step 1
Drag the ``||scene.set background image to||`` block from the ``||scene.scene||`` section to the workspace.
Place it in the ``||loops.On Start||`` event.
Click the Grey box to choose a background from the Gallery.

```blocks
scene.setBackgroundImage(img``)

```
## Step 2 

Drag the ``||Sprites.Set MySprite to||`` command from ``||Sprites.Sprites||`` section to the workspace.
Place it under the background command.
Click the Grey Box to choose a Sprite from the Gallery.

```blocks
scene.setBackgroundImage(img``)
let mySprite = sprites.create(img``, SpriteKind.Player)
```

## Step 3

Drag the ``||controller.Move MySprite with buttons||`` command from the ``||controller.controller||`` section to the workspace.
Place under the ``||Sprites.Set MySprite to||`` command.

```blocks
scene.setBackgroundImage(img``)
let mySprite = sprites.create(img``, SpriteKind.Player)
controller.moveSprite(mySprite, 100, 100)
```
## Finish, Now test your game.
## Can you move your Sprite around the screen?
## How can you make it move faster or slower?  Test you ideas...



