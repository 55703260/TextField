TextField
=========

import flash.text.*;



var txt:TextField=t;

var maxLength:Number=100;



function setText(val:String):void{

        txt.width=1000;

        txt.htmlText=val;

        txt.width=txt.textWidth+4;

        if(txt.width>maxLength){

                txt.width=maxLength;

                txt.autoSize=TextFieldAutoSize.LEFT;

        }

}



setText("<p align='center'>hi~ffasddddddddfasdfasd<br/>fadfsa<br/>sdf</p>");
