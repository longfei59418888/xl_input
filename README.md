# title

###  安装
```js
    npm install xl_input
```

### 使用
```js
   <Number
        ref={(input) =>{
            this.input = input
        }}
        placeholder='sdfsf'
        style={{paddingLeft:'10px'}}
    
        // onFocus={(a,b)=>{console.log(a,b)}}
        // onKeyUp={(a,b)=>{console.log(a,b)}}
        // onBlur={(a,b)=>{console.log(a,b)}}
        // onChange={(a,b)=>{console.log(a,b)}}
        proxy={(a)=>{  // 拦截输入
            return a
        }}
        onEnter={(a)=>{
            console.log(a)
        }}
    />
    <div>
        <p onClick={()=>{
            console.log(this.input.value)
        }}>enter</p>
    </div>

```














