## FLV-Playerのテンプレート
* * *
**デザインのカスタマイズしやすめ**  

ライブラリ内  
images/  
+ handle  
+ on  
+ off  
+ play  
+ pause  
+ poster  
とか上書きして。。  

flashvarsで指定。  
  
var flashvars =  
{  
　movie: 'video/movie.flv',    
　auto: 'true',    
　mute: 'false'   
};  
  
※指定無しで。   
+ movie: 'movie.flv'  
+ auto: 'false'  
+ mute: 'false'