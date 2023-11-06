# Popup-panel-Css+Html


.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    flex-wrap: wrap;
    
}



.table{

    border-collapse: collapse;
    width: 80%;
    margin:0 auto;
    background-color: #BADFF2;
    align-items: center;
    border: 1px solid black;
    
}
.th{
    border: 1px solid black;
    height: 50px;
    width: 30px;
    
    
}
.td{
    padding: 10px;
    border: 1px solid black;
    text-align: center;
    background-color: rgb(248, 251, 254);
    
}


.update{
    display:flex;

    width: 100%;
    padding: 8px 12px;
    background-color: #BADFF2;
    
    justify-content: center;
    
    border:none;
    border-collapse: collapse;
    font-size: 14px;
    
}


    


.update:hover{
    background-color: #e2e2e2;
}

.tr:hover td{
    background-color: #e2e2e2;
}

.popup-container{
    border: 2px solid #f1f1f3;
    border-radius: 4px;
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    width: 25%;
    margin: 0 auto;
    min-height: 350px;
    min-width: 350px;
    text-align: center;
    justify-content: center;
    background-color: #BADFF2;
    color:#172641;
    
    position: absolute;
    left: 35%;
    top: 20%;
    z-index: 1;
}
.header-popup{
    font-family: Georgia;
}
.update-popup{
    background-color: #f1f1f3;
    color: #172641;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;

    border: none;
    border-radius: 4px;
    margin :0 auto;
    padding: 0;
    position: relative;
    top: 15px ;
    bottom: 15px;


    display: flex;
    align-items: center;
    justify-content: center;
    height: 30px;
    width: 100px;
      


}

.input-popup{
    margin-top: 5px;
    border: 1px solid aliceblue;
    border-radius: 4px;
    padding:8px;
    
}

.close{
   
    margin-left:100px; 
    


}


.items{
    display:flex;
    flex-direction: column;
    justify-content: center;
    margin-top: 10px;
    display: flex;
    
    
    text-align: center;
}
