import React, {Component} from 'react';  
import {Platform, StyleSheet, Text, View} from 'react-native';  
  
export default class App extends React.Component {
	render() {
		return(
			<view style ={style.container}>
				<text>hello world</text>
			</view>
		)
	}
}  

const styles = stylesheet.create({
	container:{
		flex: 1,
		backgroundcolor: '#fff',
		alignitems: 'center',
		justifycontent:'center',
	},

});
