# Vim Review

<br>
<br>
## Sections
  - Command Mode
  - Essentials
  - Replace
  - Basics 
  - Delete
  - Movement Basics
  - Movement Advance
  - Spellcheck
  - Search
  - Highlight
  - Complex Combos
  - Inside and around
  - Visual Mode

<br>
<br>
<br>

### Command Mode

  - enter command mode
  - save 
  - exit
  - save and exit
  - force
  - around 
  - undo
  - redo
  - repeat
  - delete and then repeat 5 times


<br>


### Essentials 

  - insert mode
  - insert at line beginning
  - insert after cursor, append
  - copy, yank 
  - delete
  - delete line
  - copy
  - copy line
  - paste after
  - paste before
  - cut
  - cut line
  - append before
  - append after
  - open new line before
  - open new line after


<br> 


### Change and Replace

  - replace
  - replace and keep typing
  - change movement: word, sentence, paragraph
  - change line
  - change from end 
  - change to question mark
  - change inside sentence
  - change to x, word, sentence, paragraph
  - substitute, delete character and insert 
  - substitute line, delete line and insert
  - delete to end of word and insert


<br>


### Basics

  - word
  - sentence
  - paragraph
  - tag
  - change
  - block

<br>

### Delete

  - delete 
  - delete before
  - d[x], x: word, sentence, paragraph
  - delete line
  - delete cursor to period
  - delete cursor to lineend 
  - join current line to next one, _delete_ between line
  - delete a word              
  - and delete 5 more time 


<br> 

 
### Movement Basics

  - move up
  - move down
  - move left
  - move right
  - move line beginning
  - move line end
  - move first none-blank character in line
  - move before next quote
  - move after next quote
  - move word
  - move one big word
  - move end of word
  - move back word
  - move back one big word
  - move sentence        
  - move one paragraph   

<br>

### Movement Advance
  - move screen top 
  - move screen middle
  - move screen bottom
  - move file top
  - move file bottom
  - move half screen up
  - move half screen down
  - page up
  - page down
  - move previous location
  - move back to original place
  - move line number
  - scroll up 
  - scroll down
  - move - half page up
  - move - half page down
  - move page up
  - move page down


<br>

### Spellcheck

  - turn on spellcheck
  - turn off spellcheck
  - next misspelled word
  - last misspelled word
  - get suggestion for misspelled word
  - mark misspelled word as correct
  - mark a good word as misspelled


<br>


### Search

  - search for string
  - up a character
  - onto a character
  - search for word under cursor
  - search and stop before
  - search and stop after
  - move to next search word 
  - replace bar with foo on line
  - global replace: bar with foo
  - previous search words        : N   
  - change foo to bar in line 5 to 15
  


<br>
<br>
<br>


### Highlight, visual selection mode
  
  - begin highlight, enter mode
  - highlight whole line
  - copy
  - copy line 
  - cut, delete 
  - paste before and paste after

<br>
<br>

### Complex functions
  - insert x characters of y
  - search for a word, append to line, move to next word, repeat
  - delete around a word
  - delete inside word
  - change inside sentence
  

<br>


### Inside and Around

  - word
  - sentence
  - paragraph
  - single quotes
  - double quotes
  - back ticks
  - parenthesis
  - brackets
  - braces
  - tags


<br>


### Visual Mode Combos

  - highlight paragraph
  - select inside parenthesis
  - select inside brackets
  - select everything inside 2nd tier braces
  - select two words and copy
  - enter line-based visual mode adn delete 2 lines below
  - select entire paragraph
  - select entire paragraph and paste below




<br>
<br>
<br>
<br>



## Solutions



<br>


### Commands

      enter command mode        : esc             
      save                      : s      
      exit                      : q     
      save and exit             : wq              
      force                     : !      
      around                    : a        
      undo                      : u     
      redo                      : Ctrl-r   
      repeat                    : .     


<br>


### Essentials 

      insert mode               : i            
      insert at line beginning  : I                        
      insert after cursor       : a                     
      copy, yank                : y            
      delete                    : dw       
      delete line               : dd            
      copy                      : y     
      copy line                 : Y          
      paste after               : p            
      paste before              : P             
      cut                       : dw    
      cut line                  : dd         
      append before             : a              
      append after              : A             
      open new line before      : o                     
      open new line after       : O                    

<br> 

### Change and Replace

      replace                                    : r
      replace and keep typing                    : R        
      change line                                : C
      change to question mark                    : ct?        
      change inside sentence                     : cis       
      change to x: word, sentence, paragraph     : c {w, s, p} 
      substitute, delete character and insert    : s                          
      substitute line, delete line and insert    : S                         

<br>

### Basics

      words     : w
      sentence  : s, )
      paragraph : p, }
      tag       : t
      change    : c
      block     : b
      
      
<br>

### Delete

      delete                              : x (exterminate)
      delete before                       : X
      d[x], x: word, sentence, paragraph  : d[w, s, p]
      delete line                         : dd
      delete cursor to period             : dt.
      delete cursor to line end           : D
      join current line to next one, _delete_ between line : J
      delete a word                       : dw
      and delete 5 more time              : 5.

<br> 

 
### Movement Basics

      move up                : k
      move down              : j
      move left              : h
      move right             : l
      move line beginning    : 0        
      move line end          : $  
      move before next quote : t"           
      move after next quote  : f"         
      move word              : w 
      move one big word      : W     
      move end of word       : e     
      move back word         : b  
      move back one big word : B
      move sentence          : )
      move one paragraph     : }    
      move first none-blank character in line  : ^           

<br>

### Movement Screen
      move screen top              : H      
      move screen middle           : M       
      move screen bottom           : L        
      move file top                : gg   
      move file bottom             : G      
      move half screen up          : ^U         
      move half screen down        : ^D           
      page up                      : ^B
      page down                    : ^F
      move previous location       : Ctrl-i            
      move back to original place  : Ctrl-o                 
      move line number             : {line-number}      
      scroll up                    : ^E
      scroll down                  : ^Y
      move - half page up          : ^U         
      move - half page down        : ^D           
      move page up                 : ^B  
      move page down               : ^F   


<br>

### Spellcheck

turn on spellcheck                  : set spell
turn off spellcheck                 : set nospell
next misspelled word                : ]s
last misspelled word                : [s 
get suggestion for misspelled word  : z= 
mark misspelled word as correct     : zg
mark a good word as misspelled      : zw


<br>


### Search
    
      search                       : /{string}      
      up a character               : t    
      onto a character             : f     
      search for word under cursor : *                  
      search and stop before       :             
      search and stop after        :            
      move to next search word     : n, ;              
      replace bar with foo on line : s /foo/bar/g                  
      global replace: bar with foo : %s /foo/bar/g
      previous search words        : N, ,
      change foo to bar in line 5 to 15 : :5,15s/foo/bar/g 

<br>


### Complex functions
      insert x characters of y  : <esc>[3]i[e]<esc>    // eee
      delete around a word      :   
      delete inside word        : 
      change inside sentence    :     
  - #### search for a word, append to line, move to next word, repeat
  

<br>


### Inside and Around

      word           : iw ar 
      sentence       : is as   
      paragraph      : ip ap    
      single quotes  : i' a'        
      double quotes  : i" a"        
      back ticks     : i` a`    
      parenthesis    : i( a(      
      brackets       : i[ a[   
      braces         : i{ a{ 
      tags           : it at


<br>


### Visual Mode Combos

      highlight paragraph         : vip 
      select inside parenthesis   : vi( 
      select inside brackets      : vi[ 
      select two words and copy   : vwwy 
      select everything inside 2nd tier braces : v2i{ 
      select entire paragraph and paste below  : vipyjjp
      enter line-based visual mode and delete 2 lines below  : Vjjd 


 
 
<br>
<br>


### Sources

      general: https://danielmiessler.com/study/vim/
      searches: http://vim.wikia.com/wiki/Search_and_replace
      markdown reader: https://chrome.google.com/webstore/detail/markdown-viewer/ckkdlimhmcjmikdlpkmbgfkaikojcbjk?hl=en






