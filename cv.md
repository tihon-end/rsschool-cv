*Name:* Vitali Tsikhanovich

*Contact* Info: telegram: tihonnet

*Skill task:*
  * HTML basics
  * CSS basics
  * JS basics
  * Git basics

*Code examples:*
``` javascript
 function calc() {

        return new Promise(function(resolve, reject){
            let request = new XMLHttpRequest()
            request.open("GET", "current.json")
        
            request.setRequestHeader('Content-type', 'application/json; charset=utf-8');
            request.send()
        
            request.onload = function() {
                if(request.readyState === 4) {
                        if(request.status == 200) {
                            resolve(this.response)
                        }
                        else {
                            reject()
```

*Education:* 
* Belarusian National Technical University
* Information Systems and Technologies
              
*English:* A2