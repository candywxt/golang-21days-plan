🎆🎆🎆 21天golang养成计划第一波
### day1:hello world
--- 学会使用go build，go install，go test,以及了解workspace。
### day2:基本语法
--- 跟着tour过了一遍基础语法。
### day3: 基本语法+1
--- 语法和js的差别还是蛮大的，看的时候觉得嗯都会了，实际写的时候就会忘记。要快速手撸各种循环判断以后的开发体验才会好。
### day4: 刷codewar
--- 过一下基础语法同时增强自己的算法能力。(go的logo越看越可爱 😄
### day5: 基本语法之：defer
---- A defer statement pushes a function call onto a list. The list of saved calls is executed after the surrounding function returns. Defer is commonly used to simplify functions that perform various clean-up actions.

1. A deferred function's arguments are evaluated when the defer statement is evaluated.
2. Deferred function calls are executed in Last In First Out order after_the surrounding function returns.
3. Deferred functions may read and assign to the returning function's named return values.（这个例子没跑通……还不太理解,例子如下）

`In this example, a deferred function increments the return value i after the surrounding function returns. Thus, this function returns 2:

func c() (i int) {
    defer func() { i++ }()
    return 1
}`


