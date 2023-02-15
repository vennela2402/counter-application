import React, {useState} from 'react'

export default function App() {
  const [count, setCount]= useState(0)
  const [disabled, setDisabled]= useState(false)
  const incrementhandler=()=>{
    setCount(count => count+1)
  }
  const decrementhandler=()=>{
    setCount(count=>count-1)
  }
  let myStyle={
    color: "green"
  }
  if(count>=5 && count<=9){
    myStyle ={
      color: "blue"
    }
  }
  if(count===10){
    myStyle={
      color: "red"
    }
  }
  return (
    <div>
      <h1 style={myStyle}>Counter</h1>
      <button onClick={incrementhandler} disabled={count >9 ? true : false}>Increment</button>
      <h1>{count}</h1>
      <button onClick={decrementhandler} disabled={count<1 ? true: false }>decrement</button>
    </div>
  )
}
