
 Use Cases

This project is useful for:

* Learning the HTML5 Canvas API
* Understanding JavaScript mouse events
* Beginner front-end practice projects
* Teaching drawing logic in web development courses
* Base project for building a full paint application

How It Works (Under the Hood)

Action       Event Used    Purpose                     
 
Start draw    mousedown    Begins a new drawing path
Drawing       mousemove    Draws lines as mouse moves 
Stop draw     mouseup      Ends the current path     
Leave canvas  mouseleave  Prevents accidental drawing
|Clear screen  clearRect() Wipes the entire canvas    



Customization

You can easily modify:

* `ctx.lineWidth` → Change brush thickness
* `ctx.lineCap` → Change brush style (`round`, `square`)
* Canvas size → Edit width & height in `<canvas>`
* Default color → Change value in the color input

Learning Outcomes

After exploring this project, you will understand:

* How canvas drawing paths work
* Real-time rendering on user input
* State management using boolean flags
* DOM interaction with input elements
* Building interactive UI without libraries

 Try These Experiments

* Add a **brush size slider**
* Add an **eraser button** (set color to white)
* Add **Save as Image** using `canvas.toDataURL()`
* Add **keyboard shortcuts** (e.g., press `C` to clear)
* Add **touch events** for mobile support
 Contributing

Contributions are welcome!

If you’d like to improve this project:

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Open a Pull Request

Show Your Support

If you like this project, give it a  on GitHub and share it with others learning web development.

 Author

Built as a practice project to demonstrate the power of the HTML5 Canvas and JavaScript events.
