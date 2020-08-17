# Install react-native-linear-gradient

```
npm install react-native-linear-gradient --save
```
Using Yarn

```
yarn add react-native-linear-gradient
```

Using npm

```
npm install react-native-linear-gradient --save
```
[Referensi](https://github.com/react-native-community/react-native-linear-gradient)

# Install react-native-twinkle

```
npm i react-native-twinkle
```


# How to Use 

```
import React from 'react';
import {View, Text} from 'react-native';
import Twinkle from 'react-native-twinkle';

class App extends React.Component {
  constructor (props) {
    super (props);
    this.state = {
      visible: false,
    };
  }

  UNSAFE_componentWillMount () {
    setTimeout (() => {
      this.setState ({
        visible: true,
      });
    }, 5000);
  }

  render () {
    return (
        <View>
          <Twinkle autoRun={true} visible={this.state.visible}>
            <Text>Wandi Pratama</Text>
          </Twinkle>
        </View>
    );
  }
}

export default App;
```
