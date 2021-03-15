function refresh() {
    document.getElementsByClassName("cp-button")[1].click();
    check()
    let ra = Math.random() * 40000
    setTimeout(function(){ refresh(); }, ra);
    console.log(ra)
}

let check_name = "Rober"
var mp3_url = 'https://media.geeksforgeeks.org/wp-content/uploads/20190531165842/Recording1514.ogg';
function check() {
    let name = document.getElementsByClassName("wide")[2].innerText
    if (name !== check_name) {
        (new Audio(mp3_url)).play().then( function () {alert("New char!");})
        check_name = name;
    }
}

refresh()
