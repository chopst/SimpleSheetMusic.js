SimpleSheetMusic.js
===================

Simple player that use pure javascript to play sheet music  
Demo Page: [http://blog.maxee.info/simplesheetmusic/example_en.html](http://blog.maxee.info/simplesheetmusic/example_en.html)  
Demo in Chnese: [中文版演示](http://blog.maxee.info/simplesheetmusic/example_cn.html)

## Usage
### 1. include SimpleSheetMusic.js
``` javascript
    <script src="SimpleSheetMusic.js"></script>
```

### 2. play sheet music
``` javascriprt
    var notes = [['C4',1],['D4',1],['E4',1],['F4',1],['G4',1],['A4',1],['B4',1],['C5',1]];
    //create player
    var player = new simple_player();
    //play sheet music
    player.play(notes);
```

See the [demo page](http://blog.maxee.info/) for more documents  
中文版请看： [详细教程](http://192.168.174.130:4000/2014/11/01/play-music-with-pure-js/)

