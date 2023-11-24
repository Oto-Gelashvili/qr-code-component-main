This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

no flexbox or grid used,cause I dont know how yet,its my first day learning CSS.

what I learn in process:
with anchors target= "blank" allow us to open links in new tab
\*{
margin:0;
padding:0;
}
its important to reset,cause css has its own default margins and padding and it will get in our way while working
pixels for small things are okay
overflow:hidden is usefull tool to hide unnecessary problems,in this case there was scroll appearing which i didnt intendt to happen.
position realtive and absolute:you set absolute position and than relative to something that you want first item to be absolute to!
margin: 0 auto; is common tool to horizontally center stuff
box-sizing:border box so size is calculated by contnent and its surrounding,not just content.
top:50%
left:50%
transform:translate(-50%,-50%); is commonly used to center both horizontaly and verticaly stuff!
html{
font-size: 62.5%; sets default to 10px instead of 16px
}
this is useful for rem usage
rems are must for typography
use ems for media queries
