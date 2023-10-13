function colorname(r,g,b,id){
    let rr=r.toString(16).padStart(2,'0');
    let gg=g.toString(16).padStart(2,'0');
    let bb=b.toString(16).padStart(2,'0');
    let elem=document.getElementById(id);
    elem.textContent="#"+rr+gg+bb;
}
function extra(r,g,b,shape,name){
    let extra1=document.getElementById(shape);
    extra1.style.backgroundColor='rgb('+r+','+g+','+b+')';
    colorname(r,g,b,name);
}
function go(){
    let r=Math.floor(Math.random()*(256));
    let g=Math.floor(Math.random()*(256));
    let b=Math.floor(Math.random()*(256));
    let bgcolor=document.querySelector('body');
    bgcolor.style.backgroundColor='rgb('+r+','+g+','+b+')';
    colorname(r,g,b,'colorname');
    let e1r=r+10;
    let e1g=g+30;
    let e1b=b+60;
    extra(e1r,e1g,e1b,'extra1','extralayout1');
    let e2r=r-10;
    let e2g=g-30;
    let e2b=b-60;
    extra(e2r,e2g,e2b,'extra2','extralayout2');
    let e3r=r+60;
    let e3g=g-30;
    let e3b=b+10;
    extra(e3r,e3g,e3b,'extra3','extralayout3');
}
