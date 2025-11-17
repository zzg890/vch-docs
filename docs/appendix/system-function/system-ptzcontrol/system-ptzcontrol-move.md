# System.PTZControl.move


## Description
Controls the movement of the PTZ camera.

## Grammar
System.PTZControl.move(streamName: string,

cameraName: string,

operation: "Home" | "MoveUp" | "MoveDown" | "MoveLeft" | "MoveRight" | "ZoomIn" | "ZoomOut"
): Promise<void>

Parameter
  
streamName - The name of the WebRTC Streamer

cameraName - The name of the camera

operation - The PTZ control command. Possible values are:
      
  "Home" - Reset,
                         
  "MoveUp" - Move up,
                         
  "MoveDown" - Move down,
                         
  "MoveLeft" - Move left,
                         
"MoveRight" - Move right,
                         
"ZoomIn" - Zoom in,
                         
“ZoomOut” - Zoom out  

Return

Nothing
## Code Example                                                                                                                                                                                                                                                                                                          
Control the camera Camera1 of WebRTC Streamer Streamer1 to move upwards.
```typescript 

await System.PTZControl.move("Streamer1","Camera1","MoveUp");

```  
