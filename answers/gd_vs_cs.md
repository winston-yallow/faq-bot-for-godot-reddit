Hi, I'm a baby community bot!, 

I have reason to believe from your title that you're looking for the difference between GDScript and C#? If not, please ignore me. 

If so, welcome to Godot!! This is a very common question, and I'm here to help.

**Pros of GDScript**
* Simple with easy syntax(Syntax resembles python's).
* Native engine support. All project exports work with it(Desktop/Mobile/Web). Though C# is catching up.
* More Godot tutorials and resources for learning it.
* Smaller build size. Though it becomes negligible with larger projects.
* Dynamic typing, with optional type hints.

**Pros of C#**
* Faster execution speed. Note API calls are passed to the engine(C++), so you won't necessarily gain speed just using C#. You will notice a difference if you have lots of large calculations/loops or code not making engine calls.
* More familiar to those coming from Unity or other C# backgrounds and vice versa.
* Better IDE support, which means better refactoring.
* Nuget packages are also available to use. These are C# libraries that can be added to your project.
* Statically typed

**Note that you can use both in the mono/.NET built!** There's also the [differences listed in the docs](https://docs.godotengine.org/en/stable/tutorials/scripting/c_sharp/c_sharp_differences.html), as well as a [Duck Duck Go](https://duckduckgo.com/?q=reddit+gdscript+vs+c%23), and [Google](https://www.google.com/search?q=reddit+gdscript+vs+c%23) search. The info should be accurate enough for your needs, so long as it says Godot 4.0. 

If you're ready to start your journey, a great place is with making *Dodge the Creeps*, which [lives in the docs](https://docs.godotengine.org/en/stable/getting_started/first_2d_game/index.html). The docs are your best friend for working with Godot! [AwesomeGodot](https://github.com/godotengine/awesome-godot) is also a great place for assets, projects, tutorials, etc.

**Planned bot features**:
Provide a list of top and new posts on the topic; Provide answers to other FAQs; Count the number of times GDScript VS C# is mentioned in the past week, as well as total bot replies.)