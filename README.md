# Add QR Codes on Website   

The following javascript code will generate QR code image for the current webpage. Suggest using it on the header of the webpage.

```javascript
<a href="javascript:(function(){var%20qrSrc='https://chart.googleapis.com/chart%3Fchs=250x250%26cht=qr%26chl='+encodeURIComponent(document.location.href),overlay=document.createElement('div'),os=overlay.style,img=document.createElement('img');img.src=qrSrc;os.position='fixed';os.zIndex=1000;os.width='100%25';os.height='100%25';os.top=0;os.left=0;os.textAlign='center';os.backgroundColor='rgba(0,0,0,0.9)';img.style.marginTop='100px';overlay.appendChild(img);document.body.appendChild(overlay);overlay.addEventListener('click',function(){document.body.removeChild(overlay);})})();">
     <img border="0" src="http://scan2d.com/tools/share-icon.png" width="30" height="30">
 </a>
```

## Online Demo   

go to [Scan2d.com](http://scan2d.com) for an online demo. 

## Why we need it   
* Right now iPhone, Facebook and Twitter app all have built-in QR code scanner.  The end user can open any of your webpage in the smart phone.
* People may have gotten interrupted or rushed to complete another task. A QR code allow the user to scan and open the same link on smart phone, so that they can pick up what he left out and continue reading.
* Smart phone provide various features, which can not be found on the desktop. The user can share the webpage by email, SMS, facebook, twiiter etc.
* Making your website accessible on smart phones means your clients can access your website anytime, anywhere. Any important information is at their fingertip, such as your business hours, your location, and a contact number. Help the client avoid having to type long URL and make it easier for them to open it on their phone. 


Check [Scan2d.com](https://scan2d.com) for more details.
