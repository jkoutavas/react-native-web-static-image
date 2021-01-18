# react-native-web-static-image
This is an attempt to display a static image from react-native-web. This repo was created to demonstrate the problem I'm having in succeeding.

The app was created by following the steps at [this article](https://medium.com/@aureliomerenda/create-a-native-web-app-with-react-native-web-419acac86b82), then I `yarn add customize-cra react-app-rewired` using info from [this article](https://mmazzarolo.com/blog/2020-10-24-adding-react-native-web/) so I may apply the `url-loader` webpack rule mentioned in [react-native-web issue #1497](https://github.com/necolas/react-native-web/issues/1497) to get a static image to load using `<image source={require(...)}>`

It's at [this line of code](https://github.com/jkoutavas/react-native-web-static-image/blob/7744f7687704f552a7f1906758dc8612e4410d67/app/src/App.js#L54) where I do the image display.

It's [here](https://github.com/jkoutavas/react-native-web-static-image/blob/570880720deed489bb4cb49b115f2c4e20dc9364/app/config-overrides.js#L5) where I'm adding a url-loader webpack rule, as referred to at [react-native-web issue #1497](https://github.com/necolas/react-native-web/issues/1497) and similar solutions I've seen online.
