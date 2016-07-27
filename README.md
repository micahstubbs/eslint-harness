## eslint-harness

want to have clean code, but don't want to setup and configure [eslint](http://eslint.org/) from scratch? me too.

#### setup

`git clone git@github.com:micahstubbs/eslint-harness.git`

`npm i`

#### usage

`test.js`

```javascript
export default function () {
  // paste the javascript you want to lint here 
}
```

in the root directory of this project, run the command

`npm run lint`

you probably see some style errors

![style errors](http://i.imgur.com/VZ9yuqt.png)

fix the errors in the terminal

then you should see a new prompt, with no more errors 😄
![no more errors](http://i.imgur.com/nw3WYQb.png)

🎉 now you have nice freshly linted [ES2015](https://babeljs.io/docs/learn-es2015/) in the [Airbnb style](https://github.com/airbnb/javascript)

you can now copy the body of that function in `test.js` and go paste it back into your project
