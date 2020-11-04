# styling.css

* {
    box-sizing: border-box;
   
}


h1 {
    text-align: center;
    font-size: 1.75em;
}

h2 {
    border: 3px solid black;
    font-size: 1.25em;
    text-align: center;
    float:right;
    padding-left: 30px;
    padding-right: 30px;
    position: relative;
    right: 10px;
    bottom: 5px;
    width: 150px;
    margin-bottom: auto;

}

p {
    margin: 10px;
    border: 3px solid black;
    background-color:gray;
    padding-top: 50px;
    padding-left: 10px;
    padding-right:10px;

}

.chicken {
    background-color:pink;
}

.beef {
    color: white;
    background-color: red;
}

.sushi {
    background-color: yellow;
}


/* Simple Responsive Framework. */
.row {
  width: 100%;
}

/********** Large devices only **********/
@media (min-width: 992px) {

  .col-lg-4 {
    float: left;
  }

  .col-lg-4 {
    width: 33.33%;
  }

}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {

  .col-md-6, .col-md-12 {
    float: left;
}

  .col-md-6 {
    width: 50%;
  }

  .col-md-12 {
    width: 100%;
  }
}

/********** Small devices only **********/
@media (max-width: 767px) {

.col-sm-12 {
    float: left;
}
.col-sm-12{
    width: 100%;
}

h2 {
    bottom: 15px;
}
}


