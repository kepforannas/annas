## First Project
Hi guys, this is my first project, please forgive me if there are any mistakes, guys✨, this script was created since Thursday, jun 3, 2025. Don't forget to give stars and follow me😄🐈‍⬛
## Thank you to those who have helped me ✨

- [`Annas`](https://github.com/KepForAnnas) Anas ( crator )
- 

```javascript
console.log("anti aldog 🐕")
```

## A Few Tips for Using Buttons
- to display the "Button List" view
```javascript
let buttons = new Buttons();
buttons.setBody("ngapain bg?");
buttons.addSelection("List Menu");
buttons.makeSections("#! - Show All Menu List!!", "");
buttons.makeRow(
    "#! - Show All Menu",
    "display all menu in the bot !!!",
    "you can see all the features in this bot",
    `${prefix}menuall`
);
await buttons.run(m.chat, client, m);
```
- to display the "Button Copy" view
```javascript
let buttons = new Buttons();   
buttons.setBody("ngapain bg?");
buttons.addCopy("Copy", `puqi`);
await buttons.run(m.chat, client, m);
```
## To change/modify the bot's display section, you can go to:
```javascript
("./start/lib/buttondoc.js")
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.






 

l