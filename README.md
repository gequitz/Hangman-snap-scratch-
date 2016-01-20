<?xml version="1.0"?>

-<project version="1" app="Snap! 4.0, http://snap.berkeley.edu" name="Gabriel_Equitz_hangman_project">

<notes/>

<thumbnail>data:image/png;base64,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</thumbnail>


-<stage name="Stage" id="1" scheduled="false" inheritance="false" codify="false" lines="round" threadsafe="false" tempo="60" costume="0" height="360" width="480">

<pentrails>data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAeAAAAFoCAYAAACPNyggAAAOhUlEQVR4Xu3VwQkAAAjEMN1/abewn7jAQRC64wgQIECAAIF3gX1fNEiAAAECBAiMAHsCAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQICLAfIECAAAECgYAAB+gmCRAgQICAAPsBAgQIECAQCAhwgG6SAAECBAgIsB8gQIAAAQKBgAAH6CYJECBAgIAA+wECBAgQIBAICHCAbpIAAQIECAiwHyBAgAABAoGAAAfoJgkQIECAgAD7AQIECBAgEAgIcIBukgABAgQIHLFxAWmhEwHPAAAAAElFTkSuQmCC</pentrails>


-<costumes>

<list id="2"/>

</costumes>


-<sounds>

<list id="3"/>

</sounds>

<variables/>

<blocks/>

<scripts/>


-<sprites>


-<sprite draggable="true" name="Sprite" id="8" costume="1" pen="tip" color="80,80,80" rotation="1" scale="1" heading="90" y="-99" x="-14" idx="1">


-<costumes>


-<list id="9">


-<item>

<costume name="Untitled" id="10" image="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACgAAABTCAYAAADtG0VvAAAGDklEQVRoQ+2aech+QxTHP5IQ2UJIdlEIoUj2rNkSkn0JCdkSkl22bAmJ7FtCfih71hJlX8qSPSRkiUhIH85oXM/zztx75+cv33p7n3mee2c+98zMmTNn7hwM11rAfsCmgJ9zvQI8CdwI+Hmw5hhwp0CXTICaVpWAxwRw7+b6AC4UYPv3buWvG24I0G/73F8LKNwTHat9B8yKhu3OXDsD6W/B7AetuRlQDVkLaMVrZg3dC2jJUkM+mJbbqQO5dq0VawBPB07LKjwgGq1tw+t8mOuzG84ArLeoEqCz8+WsFgf7pcVaJ19wdIzh9KtWLM7wEqDdoytRT4VLGcj3522O1U2iAl1QccLNBOj4+QDwv6p64gJ93iOO3+VL43gmwHzcvNrD75Us/CGwbFxUHM8zAeaTo3pQl+hicqRJV6z3f8AJFu3VM/9b8L+yYJXPqpggXpL71lGTpLuKLFzyWRWA+tRvsuuKvrW0kuRBwphlLjHly12Vby0B5hXq+X1iHe0QLRfrelqZqh64BChIbsXe8Vw8STeerLKe99YAdseikC5RxUgk4LzfUCvftxTHXuqiGkCv7cZzfqfDdXZP63K71EioG/cV1998/NQCJkhjwTyET0PA0D/J7py003OL4JjWzVSrD6CV2k1CppiutiFjSeFqh8Xf9fYFTDe6IbLb873GJFj3Lj5Qd1NV+2BVk2SmylJ3bgPMFX/zALcFVGlTVQQdasFuxScDZ8eX5wCWm6gV4PHABUF0IWC5iVoBHpXt9i4DLDdRK8DDgCuD6CrAchO1AjwQuDaIrgMOakJXudTVtLU3cHNceCtguYlaWXB34I4guhOw3EStAHXc9wSRztlyE7UC3BZ4IIgeBLZrQtdwDG4BPBZQjwOWm6iVBTcCng6il4B1mtA1sKCB5+rAO8BzGdRZwKktIIdaULBjw528AewLaLmu9shm9yDevoA5WN6g+9s8C5v/5uw+BXhzCGEt4DQw27wF0PfpXtRXwKITYAZ1ewmwBHZxbCWXAT4KqE9ikgh0aAf03bBmcupFo04DrAVLDSwBfB6FLwDLyiMHQTfskFR3exewL1hqdxHg6yiY2rCc64gIaLsbrmK3J8ChYAliPuCHKPwIzD+h7xYLa/bqdgFvAvaZUKGDP42x0lhxP/JLXPRr7E2m3dOr2wXU0b6e1dYHLIf4PXP8cwKWZ1JVt6cuNgq2m2otNqnhn4G544d5AcslFbs9AQrn2BkjMwcLRAVOhu97VDat22eV/GCPNvgyc9CLw5/lvup2+9otAT8FlgqipQHLQ5S6/SfPl1sCemxmRkutEMdoQwD/cU9LwLeAVaL2VYG3R9M1iAdzhteANeILD78tj1ZLC76QRdLrAZZHqyXgs8AGQWRwYHm0WgLmh9X6tcE5wfypWgI+DGwVlW8NPDLafI0nyf3A9gG1I2B5tFpa8G5glyDaFbA8Wi0Bbwfcxak9Acuj1RLQMxO3n8oEu+XRagl4NXBwEB0CXDOarvEkuRw4PKCOBCyPVgsLphjQpS29bvIisO5ougYWNLR3D+K5iCHWxhmU0flxYyHHWtBsgj5PvQ8Y6i+ZQZ0EnDcGcgyguWjdSZLJJN/M7O4STaibWB+koYD5jLVhU21uwpPMsno8ljR4ZRkC6NjyOD/pfODEjnmcOGZaUyLTHZ4BRJ5DrLJoX8AzI/mTKr8CcKMzSSsGpIkl9TGwOfBeFVlc1AfwhM6A92Da0/OZtH68++oJqNL9CFm9Ja0F1AHnjvcuYLdKS+wA3Jdd+xDgqUCVagC77yv0aiAo8qMyv/JUKq3bM4KWAA2bzJ4mPRNBaU1ao9uwE+nc7MsqRz4ToG5Cd5Hky7ZGzKZ4h+qiSL6n+4uOfBqg5x6G7Glwm7oVbuhbR/kD9XLkkwBNZgqXEuGfBdygLP0UU1c78i7gygGXUhi6Ay33/NA+nXJftSPPAU38aLnVotLfAs4VYXao68htY6WuI0+APpH5vVy+E5P7r9kB2XXktmEC/u93DHMLGpkYoai9IsabHVDdOnNH/q92u2Nwy0ihNdlP9Hg6HbkHQI927/kD/LQ/QuKgigYAAAAASUVORK5CYII=" center-y="106" center-x="62"/>

</item>

</list>

</costumes>


-<sounds>

<list id="11"/>

</sounds>

<variables/>

<blocks/>


-<scripts>


-<script y="10" x="38">

<block s="receiveGo"/>


-<block s="doSetVar">

<l>WordSoFar</l>


-<block s="reportNewList">

<list/>

</block>

</block>


-<block s="doSetVar">

<l>LetterUsed</l>


-<block s="reportNewList">

<list/>

</block>

</block>


-<block s="doSetVar">

<l>MaxNumberOfWrong</l>

<l>8</l>

</block>


-<block s="doSetVar">

<l>NumberOfWins</l>

<l>0</l>

</block>


-<block s="doSetVar">

<l>MyWordLength</l>

<l>0</l>

</block>


-<block s="doSetVar">

<l>FirstTime</l>

<l>true</l>

</block>


-<block s="doSetVar">

<l>LetterIsInWord</l>

<l>false</l>

</block>


-<block s="doSetVar">

<l>WordIndex</l>

<l>0</l>

</block>


-<block s="doSetVar">

<l>MyWord</l>


-<block s="reportNewList">


-<list>

<l>sports</l>

<l>forever</l>

<l>language</l>

<l>homework</l>

<l>program</l>

</list>

</block>

</block>


-<block s="doDeleteFromList">


-<l>

<option>all</option>

</l>

<block var="LetterUsed"/>

</block>


-<block s="doDeleteFromList">


-<l>

<option>all</option>

</l>

<block var="WordSoFar"/>

</block>


-<block s="doSetVar">

<l>LetterIndex</l>

<l>0</l>

</block>


-<block s="doSetVar">

<l>MyWordLength</l>


-<block s="reportStringSize">

<block var="PickedWord"/>

</block>

</block>


-<block s="doSetVar">

<l>WordIndex</l>

<l>1</l>

</block>


-<block s="doSetVar">

<l>GuessesLeft</l>

<block var="MaxNumberOfWrong"/>

</block>


-<block s="doForever">


-<script>


-<block s="doIf">


-<block s="reportGreaterThan">

<block var="WordIndex"/>

<l>5</l>

</block>


-<script>


-<block s="doSayFor">

<l>All words have been played. Click flag to restart all!</l>

<l>3</l>

</block>


-<block s="doStopThis">


-<l>

<option>all</option>

</l>

</block>

</script>

</block>


-<block s="doSetVar">

<l>PickedWord</l>


-<block s="reportListItem">

<block var="WordIndex"/>

<block var="MyWord"/>

</block>

</block>


-<block s="doSetVar">

<l>MyWordLength</l>


-<block s="reportStringSize">

<block var="PickedWord"/>

</block>

</block>


-<block s="doIf">


-<block s="reportEquals">

<block var="FirstTime"/>

<l>true</l>

</block>


-<script>


-<block s="doSetVar">

<l>WordSoFar</l>


-<custom-block s="MakeDashedWord %s">

<block var="MyWordLength"/>

</custom-block>

</block>


-<block s="doSetVar">

<l>FirstTime</l>

<l>false</l>

</block>

</script>

</block>


-<block s="doSayFor">


-<block s="reportJoinWords">


-<list>

<l>Word So Far:</l>


-<custom-block s="ListToWord %s">

<block var="WordSoFar"/>

</custom-block>

</list>

</block>

<l>1</l>

</block>


-<block s="doIf">


-<block s="reportGreaterThan">

<block var="GuessesLeft"/>

<l>0</l>

</block>


-<script>


-<block s="doAsk">

<l>Enter your guess</l>

</block>


-<block s="doUntil">


-<block s="reportEquals">


-<block s="reportStringSize">

<block s="getLastAnswer"/>

</block>

<l>1</l>

</block>


-<script>


-<block s="doAsk">

<l>Enter just one letter</l>

</block>

</script>

</block>


-<block s="doIfElse">


-<block s="reportListContainsItem">

<block var="LetterUsed"/>

<block s="getLastAnswer"/>

</block>


-<script>


-<block s="doSayFor">


-<block s="reportJoinWords">


-<list>

<block s="getLastAnswer"/>

<l> has been used already</l>

</list>

</block>

<l>1</l>

</block>

</script>


-<script>


-<block s="doAddToList">

<block s="getLastAnswer"/>

<block var="LetterUsed"/>

</block>

</script>

</block>


-<block s="doSetVar">

<l>LetterIndex</l>

<l>0</l>

</block>


-<block s="doSetVar">

<l>LetterIsInWord</l>

<l>false</l>

</block>


-<block s="doRepeat">

<block var="MyWordLength"/>


-<script>


-<block s="doChangeVar">

<l>LetterIndex</l>

<l>1</l>

</block>


-<block s="doIf">


-<block s="reportEquals">


-<block s="reportLetter">

<block var="LetterIndex"/>

<block var="PickedWord"/>

</block>

<block s="getLastAnswer"/>

</block>


-<script>


-<block s="doReplaceInList">

<block var="LetterIndex"/>

<block var="WordSoFar"/>

<block s="getLastAnswer"/>

</block>


-<block s="doSetVar">

<l>LetterIsInWord</l>

<l>true</l>

</block>

</script>

</block>

</script>

</block>


-<block s="doIf">


-<block s="reportEquals">

<block var="LetterIsInWord"/>

<l>false</l>

</block>


-<script>


-<block s="doSayFor">


-<block s="reportJoinWords">


-<list>

<block s="getLastAnswer"/>

<l> is not in word</l>

</list>

</block>

<l>1</l>

</block>


-<block s="doChangeVar">

<l>GuessesLeft</l>

<l>-1</l>

</block>

</script>

</block>


-<block s="doSayFor">


-<block s="reportJoinWords">


-<list>

<l>Word so far:</l>


-<custom-block s="ListToWord %s">

<block var="WordSoFar"/>

</custom-block>

</list>

</block>

<l>1</l>

</block>

</script>

</block>


-<block s="doIfElse">


-<block s="reportEquals">

<block var="GuessesLeft"/>

<l>0</l>

</block>


-<script>


-<block s="doSayFor">

<l>You have been hanged! Press space bar to play again!</l>

<l>3</l>

</block>


-<block s="doWaitUntil">


-<block s="reportKeyPressed">


-<l>

<option>space</option>

</l>

</block>

</block>

<custom-block s="ReinitializeVariables"/>


-<block s="doChangeVar">

<l>WordIndex</l>

<l>1</l>

</block>

</script>


-<script>


-<block s="doIf">


-<block s="reportEquals">


-<custom-block s="CheckWord %s">

<block var="WordSoFar"/>

</custom-block>

<l>false</l>

</block>


-<script>


-<block s="doChangeVar">

<l>NumberOfWins</l>

<l>1</l>

</block>


-<block s="doSayFor">

<l>You guessed the word! Press space bar to play again!</l>

<l>3</l>

</block>


-<block s="doWaitUntil">


-<block s="reportKeyPressed">


-<l>

<option>space</option>

</l>

</block>

</block>

<custom-block s="ReinitializeVariables"/>


-<block s="doChangeVar">

<l>WordIndex</l>

<l>1</l>

</block>

</script>

</block>

</script>

</block>

</script>

</block>

</script>

<comment y="36" x="228" collapsed="false" w="90">Initialization of variables</comment>

<comment y="160" x="309" collapsed="false" w="90">list of 5 word.</comment>

<comment y="1248" x="348" collapsed="false" w="90">check if word has no dashes (means it is correct)</comment>

<comment y="743.8333363333334" x="429.000003" collapsed="false" w="90">check if letter has been used, if not add it to the list of letters used.</comment>

<comment y="401" x="447" collapsed="false" w="90">Go over the list of words as the game progresses Stop program if all words have been played..</comment>

<comment y="621" x="497" collapsed="false" w="90">Ask for a guess and if more than one character is given, continue asking. </comment>

<comment y="975" x="459" collapsed="false" w="90">replace dashes by a letter that is guessed correctly.</comment>

<comment y="1316" x="453" collapsed="false" w="90">If word is correct, ask user to press space bar to play the next word.</comment>

<comment y="1114" x="500" collapsed="false" w="90">if user is hanged, ask to press space bar to go to the nexxt word.</comment>

</scripts>

</sprite>

<watcher color="243,118,29" y="294.00002399999994" x="17" var="MyWordLength" hidden="true" style="normal"/>

<watcher color="243,118,29" y="16.000001999999995" x="15" var="MyWord" hidden="true" style="normal"/>

<watcher color="243,118,29" y="34.00001199999997" x="345" var="LetterUsed" hidden="true" style="normal"/>

<watcher color="243,118,29" y="167.00000599999998" x="13" var="LetterIndex" hidden="true" style="normal"/>

<watcher color="243,118,29" y="221.00000999999997" x="11" var="WrongGuess" hidden="true" style="normal"/>

<watcher color="243,118,29" y="262.000002" x="8" var="WordIndex" hidden="true" style="normal"/>

<watcher color="243,118,29" y="48.00000399999999" x="177" var="PickedWord" hidden="true" style="normal"/>

<watcher color="243,118,29" y="6.000013999999965" x="171" var="MaxNumberOfWrong" hidden="true" style="normal"/>

<watcher color="243,118,29" y="84.000002" x="168" var="LetterIsInWord" hidden="true" style="normal"/>

<watcher color="243,118,29" y="154.00000799999998" x="347" var="WordSoFar" hidden="true" style="normal"/>

<watcher color="243,118,29" y="10" x="10" var="FirstTime" hidden="true" style="normal"/>

<watcher color="243,118,29" y="28" x="26" var="GuessesLeft" style="normal"/>

<watcher color="243,118,29" y="29" x="324" var="NumberOfWins" style="normal"/>

</sprites>

</stage>

<hidden/>

<headers/>

<code/>


-<blocks>


-<block-definition s="ListToWord %'MyList'" category="other" type="reporter">

<header/>

<code/>


-<inputs>

<input type="%s"/>

</inputs>


-<script>


-<block s="doDeclareVariables">


-<list>

<l>i</l>

</list>

</block>


-<block s="doDeclareVariables">


-<list>

<l>output</l>

</list>

</block>


-<block s="doSetVar">

<l>i</l>

<l>1</l>

</block>


-<block s="doSetVar">

<l>output</l>

<l/>

</block>


-<block s="doRepeat">


-<block s="reportListLength">

<block var="MyList"/>

</block>


-<script>


-<block s="doSetVar">

<l>output</l>


-<block s="reportJoinWords">


-<list>

<block var="output"/>


-<block s="reportListItem">

<block var="i"/>

<block var="MyList"/>

</block>

</list>

</block>

</block>


-<block s="doChangeVar">

<l>i</l>

<l>1</l>

</block>

</script>

</block>


-<block s="doReport">

<block var="output"/>

</block>

</script>


-<scripts>

<comment y="50.19999999999999" x="189" collapsed="false" w="90">Merge symbols to make a word</comment>

</scripts>

</block-definition>


-<block-definition s="CheckWord %'InputWord'" category="other" type="predicate">

<header/>

<code/>


-<inputs>

<input type="%s"/>

</inputs>


-<script>


-<block s="doDeclareVariables">


-<list>

<l>ContainsDashes</l>

</list>

</block>


-<block s="doSetVar">

<l>ContainsDashes</l>

<l>false</l>

</block>


-<block s="doIf">


-<block s="reportListContainsItem">

<block var="InputWord"/>

<l>-</l>

</block>


-<script>


-<block s="doSetVar">

<l>ContainsDashes</l>

<l>true</l>

</block>

</script>

</block>


-<block s="doReport">

<block var="ContainsDashes"/>

</block>

</script>


-<scripts>

<comment y="50.19999999999999" x="242" collapsed="false" w="90">Check if word contains dashes</comment>

</scripts>

</block-definition>


-<block-definition s="MakeDashedWord %'NumberOfDashes'" category="other" type="reporter">

<header/>

<code/>


-<inputs>

<input type="%s"/>

</inputs>


-<script>


-<block s="doDeclareVariables">


-<list>

<l>ThisDashedList</l>

</list>

</block>


-<block s="doSetVar">

<l>ThisDashedList</l>


-<block s="reportNewList">

<list/>

</block>

</block>


-<block s="doRepeat">

<block var="NumberOfDashes"/>


-<script>


-<block s="doAddToList">

<l>-</l>

<block var="ThisDashedList"/>

</block>

</script>

</block>


-<block s="doReport">

<block var="ThisDashedList"/>

</block>

</script>


-<scripts>

<comment y="114.19999999999999" x="210" collapsed="false" w="90">Build a word with a given number of dashes</comment>

</scripts>

</block-definition>


-<block-definition s="ReinitializeVariables" category="other" type="command">

<header/>

<code/>

<inputs/>


-<script>


-<block s="doSetVar">

<l>FirstTime</l>

<l>true</l>

</block>


-<block s="doDeleteFromList">


-<l>

<option>all</option>

</l>

<block var="LetterUsed"/>

</block>


-<block s="doDeleteFromList">


-<l>

<option>all</option>

</l>

<block var="WordSoFar"/>

</block>


-<block s="doSetVar">

<l>GuessesLeft</l>

<block var="MaxNumberOfWrong"/>

</block>


-<block s="doSetVar">

<l>LetterIsInWord</l>

<l>false</l>

</block>


-<block s="doSetVar">

<l>LetterIndex</l>

<l>0</l>

</block>

</script>


-<scripts>

<comment y="32.19999999999999" x="200" collapsed="false" w="90">reinitialize some variables.</comment>

</scripts>

</block-definition>

</blocks>


-<variables>


-<variable name="MyWord">


-<list id="391">


-<item>

<l>sports</l>

</item>


-<item>

<l>forever</l>

</item>


-<item>

<l>language</l>

</item>


-<item>

<l>homework</l>

</item>


-<item>

<l>program</l>

</item>

</list>

</variable>


-<variable name="PickedWord">

<l>forever</l>

</variable>


-<variable name="MyWordLength">

<l>7</l>

</variable>


-<variable name="LetterIndex">

<l>7</l>

</variable>


-<variable name="WordSoFar">


-<list id="392">


-<item>

<l>f</l>

</item>


-<item>

<l>-</l>

</item>


-<item>

<l>-</l>

</item>


-<item>

<l>-</l>

</item>


-<item>

<l>-</l>

</item>


-<item>

<l>-</l>

</item>


-<item>

<l>-</l>

</item>

</list>

</variable>


-<variable name="WrongGuess">

<l>0</l>

</variable>


-<variable name="LetterUsed">


-<list id="393">


-<item>

<l>l</l>

</item>


-<item>

<l>f</l>

</item>

</list>

</variable>


-<variable name="MaxNumberOfWrong">

<l>8</l>

</variable>


-<variable name="WordIndex">

<l>2</l>

</variable>


-<variable name="GuessesLeft">

<l>7</l>

</variable>


-<variable name="LetterIsInWord">

<l>true</l>

</variable>


-<variable name="NumberOfWins">

<l>0</l>

</variable>


-<variable name="FirstTime">

<l>false</l>

</variable>

</variables>

</project>
