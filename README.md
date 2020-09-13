### css rules :

    1.  header p{declaration}
    2. .comment div{declaration}
    3.  li {declaration}
    
 ###  styles :
  
    1. Embedded Style :
    
       <style>
        .welcome
        {
            font-size:10px;
        }
       </style> 
      
      <body>
        <p class="welcome">welcome</p>
      </body>
      
      
      
    2. inline style
    
    
    3. classes & ids 
    
      classes -> .
      ids -> #
      
      
### Targeting multiple elements :
     p,li,span
     {
     color: red;
     font-size : 14 px;
    }
    
    
 ### The important declaration:
     p{
     
     color:red:important;
     }
     
     
### Descendant 
        #main-content #sub content p{
         color: red;
        
        } 
        
        
        
### Child Selectors :
    main-content>p{
       color:red;
    }; 
    
    
### Adjacent Selectors :
    #all-articles h2+p{
           color:green;  
    } 
    
    
### Attribute Selectors :
     span[class~="deck"]{
         color:purple;
     }
     
     div[id]{
      background: gray;
     }
     
     a[title="search engine"]{
       color:red;
     }
     
     a[href$=PDF]{  # this worls all item whos end with pdf
       color:green;
     }
     
     for start use just ^ carat char.  https://www.youtube.com/watch?v=GVocONem9lw&list=PL4cUxeGkcC9gQeDH6xYhmO-db2mhoTSrT&index=18
     
     
     
 ### Pseudo Selectors:
     a: hover{
       color:red;
     }
     
     
### Hover, Active & Visited Effects:
       a:active{
         color:orange;
       
       }
       
 ### a:visited{
    color:purple;
 
 }
