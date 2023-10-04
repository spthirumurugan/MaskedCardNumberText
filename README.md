# masked-card-number

[![npm version](https://badge.fury.io/js/masked-card-number.svg)](https://badge.fury.io/js/masked-card-number)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yourusername/masked-card-number/blob/main/LICENSE)

A React Native component for masking credit card numbers.

## Installation

Install the package using npm or yarn:

```bash
npm install masked-card-number
# or
yarn add masked-card-number

Usage
Here's how you can use this component in your React Native application:

javascript
Copy code
import React from 'react';
import { View, StyleSheet } from 'react-native';
import MaskedCardNumber from 'masked-card-number';

const App = () => {
  return (
    <View style={styles.container}>
      <MaskedCardNumber
        CardNumber="1234567890123456"
        fontSize={16}
        fontFamily="Arial"
        fontWeight="bold"
        fontStyle="italic"
        color="blue"
      />
    </View>
  );
};

const styles = StyleSheet.create({
  container: {
    flex: 1,
    alignItems: 'center',
    justifyContent: 'center',
  },
});

export default App;
Props
CardNumber (string, required): The credit card number to be masked.
fontSize (number, optional): The font size for the masked card number text.
fontFamily (string, optional): The font family for the masked card number text.
fontWeight (string, optional): The font weight for the masked card number text (e.g., 'normal', 'bold', etc.).
fontStyle (string, optional): The font style for the masked card number text (e.g., 'normal', 'italic').
color (string, optional): The text color for the masked card number.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Author
Your Name

Acknowledgments
Thanks to the open-source community!