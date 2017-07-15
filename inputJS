$(document).ready(function(){
   $('.className').keyup(function (e) {
    var keyCode = e.keyCode || e.which;
    if(keyCode == 9 && e.shiftKey) {
        $(this).closest('div').previous('div').find('input:text').focus();
    }else {
       if((keyCode !== 16 && keyCode !== 9) && !e.shiftKey)
       $(this).closest('div').next('div').find('input:text').focus();
    }
 }); 
});
