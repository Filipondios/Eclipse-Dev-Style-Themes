
<h1 align="center">
  <br>
  <a href="https://www.eclipse.org/"><img src=".resources/logo.png" alt="Eclipse" width="300"></a>
  <br>
  Eclipse Dev-Style Themes & Theme Helper
  <br>
</h1>

<h4 align="center">Custom and based <a href="https://www.genuitec.com/products/devstyle/" alt="Dev-Style">Dev-Style</a> themes for eclipse and a helper for making your own color theme.</h4>

<p align="center">
  <a href="#how-to-use">How To Use ⚙</a> •
  <a href="#own-theming">Do your own Theme 🛠</a> •
  <a href="#helper">Theme Helper 🖥</a> •
  <a href="#themes">Themes 🖌</a> •
  <a href="#download">Download 📦</a> •
  <a href="#credits">Credits 📚</a> •
  <a href="#license">License 📜</a>
</p>

<img src=".resources/prev.png" alt="demo"/>

<a name="how-to-use"></a>

## How To Use ⚙

The themes are stored in the ``custom-themes`` and ``based-themes`` folders. Its pretty clear what its inside both...Once you have downloaded this repo, just follow the next steps if you are new importing themes into the dev-style eclipse plugin:
```
Open Eclipse:
-> Window -> Prefferences -> Dev-Style -> Color Themes
Then just import the themes that you want:
-> Import -> Select the .xml file of the desired theme
Restart Eclipse
```

> **Note**
> Obviously you must have installed the Dev-Style plugin wich is available in the Eclipse Marketplace as dev-style. If its not showing, try Darkest Dark Theme.

<a name="own-theming"></a>

## How to Customize your own Theme 🛠
You need to know the following "parameters" or "variables" available in the .xml files:<br><br>

``singleLineComment`` : //this is a single line comment <br>
``multiLineComment`` : /\*this is a multi-line comment\*/ <br>
<br>

 ``javadoc`` : /\*\*this is a javadoc text\*\*/<br>
 ``javadocLink`` : link to a class or other type inside a javadoc text: {@link Class}, from { to }<br>
 ``javadocTag`` : tags inside a javadoc text : @param<br>
 ``javadocKeyword`` : no idea xd, but can share the color with the javadoc tag<br>
<br>
 
 ``keyword`` : **word of the next list**: package, import, public, private, protected, class, enum, interface, module, extends, implements, final, static, this, int, float, double, char.<br>
 <br>
 
 ``class`` : color of the name of any class<br>
 ``enum`` : color of the name of any enum<br>
 ``interface`` : color of the name of any interface<br>
 <br>

``method`` : color of the name of any normal method<br>
``methodDeclaration``: color of the name of any normal method when is declared (created)<br>
``staticMethod`` : color of the name of any static method<br>
``inheritedMethod`` : color of the name of any inherited method (f.e: equals, toString (methods from superclasses))<br>
``abstractMethod`` : color of the name of any abstract method<br>
<br>

``bracket`` : [], {}, <>. ()<br>
``number`` : any number<br>
``string`` : any string typed as ""<br>
``operator`` : +,-,*,/<br>
<br>

``field`` : name of a variable that is declarated in a class (f.e: private int i, where i is colored)<br>
``staticField`` : color of a static field<br>
``staticFinalField`` : color of a static finel field<br>
``parameterVariable`` : color of a parameter in a method<br>
``localVariableDeclaration`` : color of a local variable when declared (f.e: variable inside a method)<br>
``localVariable`` : color color of a local variable<br>
``costant`` : color of a constant<br>
<br>

``lineNumber`` : color of the Eclipse editor line numbers<br>
``currentLine`` : color of the current editor line<br>
``selectionBackground`` : color of the background selected text<br>
``selectionBackground`` : color of the foreground selected text<br>
<br>

``deprecatedMember`` : color of a element when its deprecated<br>
``annotation`` : color of a Eclipse annotation<br>
<br>

> **Note**
> After reading this, you can make your custom theme by using the main ``.html`` file of this repo and then copiying the hexadecimal color values to your ``.xml`` theme file. 

<a name="themes"></a>

## Themes 🖌

<details><summary>BASED THEMES</summary>
<p>

### One Dark
![imagen](https://user-images.githubusercontent.com/91225771/199129663-f1c34680-aa63-40c5-80ba-c3029d8a6dc6.png)

## Nord
![imagen](https://user-images.githubusercontent.com/91225771/199133416-25fea3c3-0845-4eb9-a96e-b11f5680c86a.png)

### Github Dark Theme
![imagen](https://user-images.githubusercontent.com/91225771/199129783-fb262dd5-4ddd-423d-a1e1-0af2afbafdcf.png)

</p>
</details>

<details><summary>CUSTOM THEMES</summary>
<p>

### Filipondios Dark Theme I
![imagen](https://user-images.githubusercontent.com/91225771/199130396-e50ab730-1090-441a-b0c7-28e80c91acf7.png)

### Filipondios Dark Theme II
![imagen](https://user-images.githubusercontent.com/91225771/199130450-8637fddb-3c00-4468-94ef-f71088e3da99.png)

</p>
</details>

<a name="helper"></a>

## Using the Theme Helper (EDSTH) 🖥
You can access to the Theme helper or EDSTH (Eclise Dev Style Theming Herper) by clicking in the sample.html file when you have downloaded this repo files
or by accessing it in the web, with <a href="">this link</a>.

<a name="download"></a>

## Download 📦
You can git clone this repo or just download the <a href="https://codeload.github.com/Filipondios/Eclipse-Dev-Style-Themes/zip/refs/heads/main">zip</a> with all the files.

<a name="credits"></a>

## Credits 📚
Some of the themes I have in this repository are partly of fully based in existing themes. Those are
- GitHub dark theme : From <a href="www.github.com">GitHub</a>

<a name="license"></a>

## License 📜
MIT - See the license <a href="LICENSE">file</a>.

---

> GitHub [@Filipondios](https://github.com/Filipondios) &nbsp;&middot;&nbsp;
> Twitter [@filipondios](https://twitter.com/Filipondios)

