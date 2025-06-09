 import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';
import './main.css'

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(

//   <div class = "demo">sdfasfasdfasdf
//     <h1>
//       Hello world
//     </h1>
// <p class= "polo">That is incorrect</p>
//   </div>
   React.createElement ('div', null, 
      React.createElement('h1', null, 'hello wio'),
      React.createElement('h4', null, 'qiyuuuuu'),
    )
  )

;

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();
