# PROJETO--SITE-LIVRARIA-CSS

h4{
     font-size: 60px;
     font-style: normal;
     text-decoration: darkred;
     color: rgb(51, 39, 83);
     font-family: 'Times New Roman', Times, serif;
}
h1{ 

        font-size: 100px;
        font-style: normal;
        text-decoration: darkred;
        color: rgb(51, 39, 83);
        font-family: Georgia, 'Times New Roman', Times, serif;

 }


     body{
          
        font-size: 10px;

     }
     body li{
               
               padding: 10px;
               
     }  

     body li a{
                 text-decoration: black;
                 color: black;
                 
                 width: 40;


     }

     html{
           background-attachment: fixed;


     }
      
     #menu-h li{
                 display: inline;


     }

     #menu-h li a{
                 
          color: black;
          text-emphasis: none;
          display: inline-block;
          padding: 20px;
          
          
     }
     
     #menu-h{
              list-style: none;
              padding: 0;
              background-color: mediumseagreen;

     }
     .categorias ul{ 

          list-style: none;
          padding-left: 0px;
          
     }
     
     .categorias ul{ 

          width: 250px;
          padding: 5px;
          padding-left: 20px;
          font-size: 20px;
          background-color: rgb(102, 216, 208);
     }
     .categorias a {

          text-decoration: none;


     }

     .categorias li :hover{
          
          background-color: rgb(201, 195, 109);
          border-bottom: 1px solid black;
      }

      *{
            margin:0 ;
            padding: 0;

      }

      .slide {
           width: 5000px;
           height: 576px;
           overflow: hidden;
           border-radius: 15px;
           transform: all 0.4s;

      }
      .slides{
           width: 1024px;
           display: flex;

      }
      .image img{
           width: 1024px;
           height: 576px;

      }
      #atual{
           
           transition: all 2s;

      }
      .btn{
           position: absolute;
           color: #aaa;
           padding: 10px;
           text-align-last: center;
           display:flex ;
           align-items: center;
           justify-content: center;
           cursor: pointer;
           transition: all 0.4s;
           font-size: 1.7em;
           margin-top: -5px;

      }
      .btn:hover{
           transform: scale(1.5);

      }

      #voltar{
           top: 50%;
           left: 10%;

      }
      #next{
           top: 50%;
           right: 10%;
      }
      .balls{
           position: absolute;
           width: 1024px;
           display: flex;
           justify-content: center;
           margin-top: 45px;

      }
      .balls div{
           transition: all 0.5s;
           border: 3px solid #fff;
           padding: 6px;
           border-radius: 50%;
           margin-right: 15px;
           cursor: pointer;

      }
      .balls div:hover{
           background: #fff;

      }

      .imgAtual{
           transition: all 0.5s;
           background: #fff;

           
      }
