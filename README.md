jquery-bootstrap-countdown-timer
================================

A jquery based countdown bar using bootstraps progress bar technique.


## **Getting Started**
--------------------------------------
Download the file from [jquery.countdownTimer.js](https://github.com/vivekhas3/jquery-bootstrap-countdown-timer "source files") directory. You can download either the original version or the minified one(named as .min.js).

### **Including it in your page**
----
As this plugin is dedicated to bootstrap based responsive websites, there are a few basic guidelines to be followed:

     <div id="progressTimer"></div>
       
       <script type='text/javascript'>
         $("#progressTimer").progressTimer({
            timeLimit: 10,
            warningThreshold: 7,
            dangerThreshold: 10,
            baseStyle: 'progress-bar-success',
            warningStyle: 'progress-bar-warning',
            completeStyle: 'progress-bar-danger',
            onFinish: function() {
                alert("Timed out!!!");
            }
        });
       </script>
### **Advanced usage**
This plugin has a number of customizable features and these will be discussed one by one here:
	The following are the options that can be passed on whili initializing the plugin:
- **time_limit** - time for which the progress should last. Units in seconds.

- **warningThreshold** - seconds remaining triggering switch to warning color.

- **dangerThreshold** - seconds remaining triggering switch to danger color.

- **onFinish** - invoked once the timer expires.

- **baseStyle** - bootstrap progress bar style at the beginning of the timer.
- **warningStyle** - bootstrap progress bar style in the warning phase of the timer.
- **completeStyle** - bootstrap progress bar style at the completeion/danger phase of the timer.

   
## **Reporting an Issue**
1. Make sure the problem you're addressing is reproducible.
2. Use [http://jsbin.com](http://jsbin.com "jsbin") or [http://jsfiddle.net](http://jsfiddle.net "jsfiddle") to provide a test page.
3. Indicate what browsers the issue can be reproduced in. **Note: IE versions < 7 Compatibilty modes issues will not be addressed.**
4. Version of the plugin.

## **Contributing**
Contributions are always welcomme :)



