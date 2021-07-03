var box
function setup() {
  createCanvas(400,400);
box=createSprite(200,200,400,400)
box.shapeColor="red"
}

function draw() 
{
  background("red");
  if(keyDown(DOWN_ARROW))
  {
    box.shapeColor="yellow";

  }
drawSprites();
}
