# eventtask

Dette er min opgave om at bruge event.

        diverne inde i .div  :  console.log(e.target);

        bodyens Class="div_fire" to element  :   console.log(e.path[0].children[3]);
        
        href via path :   console.log(e.path[3].location.href);        
        
        istrusted  :     console.log(e.isTrusted);
                
        finde divs størrelse   :      console.log(e.target.getBoundingClientRect())
       
       
        
        returnValue  :   console.log(e.returnValue);
        
        bubbles   :   console.log(e.bubbles);
        
        timestamp  :   console.log(e.timeStamp);
        
        InputDeviceCapabilities  :   console.log(e.sourceCapabilities)
        
        NamedNodeMap    :   console.log(e.srcElement.attributes)
        
        
        
         De blå prikker inde i min hovedDiv er også Div'er. det betyder at nogle opgaver vil give fejl hvis der bliver trykket på et                blåt område.
