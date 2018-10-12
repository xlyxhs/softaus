# softaus
soft aus generator made by jjaenight
<!DOCTYPE html>

<html>

<head>
    
<title>OTP Fluff Generator</title>

<style type="text/css">

iframe#tumblr_controls {display:none;}

body { background:#FFF2F8; font-family:arial; font-size:10px; color:#BABABA; line-height:14px; }

a { color:#A3A3A3; text-decoration:none; }
a:hover { }

b, strong { }
i, em { }
pre { }
blockquote { }

#main { width:400px; margin:auto; }

#person1 { position:absolute; border:1px solid #D6D6D6; margin:200px 0px 0px 0px;  width:100px; padding:5px; background:#FEFFF0; font-family:arial; font-size:10px; color:#BABABA; line-height:14px; font-style:oblique;}
#person2 { position:absolute; border:1px solid #D6D6D6; margin:200px 0px 0px 150px;  width:100px; padding:5px; background:#FEFFF0; font-family:arial; font-size:10px; color:#BABABA; line-height:14px; font-style:oblique;}
#genbutt { position:absolute; border:1px solid #D6D6D6; margin:200px 0px 0px 300px;  width:100px; padding:5px 5px 5px 5px; background:#fff; cursor:pointer; text-align:center; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none;  }
#genbutt:hover { margin:201px 0px 0px 301px; }

#shitbox { position:absolute; border:1px solid #D6D6D6; padding:10px; background:#fff; margin:250px 0px 300px 0px; width:390px;}
#premise { }
#AU { }

#thanks { font-style:oblique; float:right; }

</style>

<script type="text/javascript">

function clear1() {
    
    document.getElementById("person1").value = "";
    document.getElementById("person1").style.fontStyle = "normal";
}

function clear2() {
    
    document.getElementById("person2").value = "";
    document.getElementById("person2").style.fontStyle = "normal";
}

function fluff() {
    
    var A = document.getElementById("person1").value;
    var B = document.getElementById("person2").value;
    
    var R1 = Math.floor(Math.random() * 20);
    var R2 = Math.floor(Math.random() * 11);
    
    switch(R1) {
        case 0:
        document.getElementById("premise").innerHTML = A + " is sick with a cold and can't sleep. " + B + " wakes up from " + A +"'s twisting and turning and has to entertain " + A + " somehow until they fall asleep.";
        break;
        case 1:
        document.getElementById("premise").innerHTML = B + " bakes " + A + " cookies out of love. Unfortunately " + A + " is pretty sure these cookies are a biohazard."
;
        break;
        case 2:
        document.getElementById("premise").innerHTML = A + " gets a job where " + B + " works, so they can spend more time together. But their shifts are completely different and they hardly ever see each other.";
        break;
        case 3:
        document.getElementById("premise").innerHTML = B + " is a hot sleeper, and " + A + " likes to cuddle. " + B + " constantly wakes up sweating in the middle of the night because " + A + " is glued to them.";
        break;
        case 4:
        document.getElementById("premise").innerHTML = "Every time " + A + " undresses, " + B + " notices something new and adorable about their body.";
        break;
        case 5:
        document.getElementById("premise").innerHTML = B + " is five years old and " + A + " is their babysitter. " + B + " is always into something new and odd every time, and " + A + " has to play along.";
        break;
        case 6:
        document.getElementById("premise").innerHTML = A + " wants a cat. " + B + " buys a kitty-ear headband and tries to be cute.";
        break;
        case 7:
        document.getElementById("premise").innerHTML = A + " buys a box of sweets and puts them in the cupboard. " + B + " spontaneously eats them all in the middle of the night and tries to keep it a secret.";
        break;
        case 8:
        document.getElementById("premise").innerHTML = A + " is playing with " + B + "'s hair and finds a grey hair. " + B + " then has a quarter-life crisis.";
        break;
        case 9:
        document.getElementById("premise").innerHTML = B + " always wears " + A + "'s clothes. " + A + " ends up saying 'keep it' cause " + B + " looks so cute. But " + A + " is steadily running out of clothes.";
        break;
        case 10:
        document.getElementById("premise").innerHTML = A + " and " + B + " go grocery shopping together for the first time. " + B + " excitedly fills the cart with various snacks and " + A + " wonders how to break it to them that they can't afford all this.";
        break;
        case 11:
        document.getElementById("premise").innerHTML = "A puppy follows " + A + " home, and " + A + " can't bear to part with it. " + A + " brings the puppy inside and tries to hide it from " + B + ".";
        break;
        case 12:
        document.getElementById("premise").innerHTML = A + " and " + B + " are playing rock paper scissors for the last cookie, but they tie every time. They decide to set up a grand tournament or duel to decide the winner.";
        break;
        case 13:
        document.getElementById("premise").innerHTML = A + " wants to use their laptop on the couch, but " + B + " always occupies the space in their lap.";
        break;
        case 14:
        document.getElementById("premise").innerHTML = A + " doesn't like talking on the phone, but " + B + " always calls them instead of texting. " + B + " admits that it's because they want to hear " + A + "'s voice.";
        break;
        case 15:
        document.getElementById("premise").innerHTML = A + " and " + B + " have to babysit an infant together. Their true nature as parents are revealed.";
        break;
        case 16:
        document.getElementById("premise").innerHTML = A + " and " + B + " reveal their tumblr blogs to each other. " + B + " turns out to be " + A + "'s #1 tumblr crush.";
        break;
        case 17:
        document.getElementById("premise").innerHTML = B + " drags " + A + " into the freezing cold to make a snowman.";
        break;
        case 18:
        document.getElementById("premise").innerHTML = A + " hangs mistletoe and stands under it. " + B + " doesn't know what mistletoe is and doesn't understand why " + A + " has been standing under the weird ceiling booger for ten minutes.";
        break;
        case 19:
        document.getElementById("premise").innerHTML = A + " is a bad kisser and knows it. " + B + " gives them a tutorial on kissing.";
        break;
        

    }
    
    
    switch(R2) {
        case 0:
        document.getElementById("AU").innerHTML = "Vampire AU";
        break;
        case 1:
        document.getElementById("AU").innerHTML = "College AU";
        break;
        case 2:
        document.getElementById("AU").innerHTML = "1990's AU";
        break;
        case 3:
        document.getElementById("AU").innerHTML = "Cyberpunk AU";
        break;
        case 4:
        document.getElementById("AU").innerHTML = "Apocalypse AU";
        break;
        case 5:
        document.getElementById("AU").innerHTML = "Elementary School AU";
        break;
        case 6:
        document.getElementById("AU").innerHTML = "Married AU";
        break;
        case 7:
        document.getElementById("AU").innerHTML = "Mermaid AU";
        break;
        case 8:
        document.getElementById("AU").innerHTML = "Royalty AU";
        break;
        case 9:
        document.getElementById("AU").innerHTML = "1920's AU";
        break;
        case 10:
        document.getElementById("AU").innerHTML = "Problematic Punks AU";
        break;

    }    

    
}

    
</script>

</head>    

<body>

<div id="main">
    
<form><input type="text" name="otp1" value="Person A" id="person1" onfocus="clear1()"></form>
<form><input type="text" name="otp2" value="Person B" id="person2" onfocus="clear2()"></form> 
<div id="genbutt" onclick="fluff()">Click for some fluff</div>

<div id="shitbox">
    
<b>Premise:</b>
<span id="premise"></span>
<br /><br />
<b>Bonus:</b>
<span id="AU"></span>
<br /><br />
<div id="thanks">(<a href="http://kogami.tumblr.com">kogami</a>)</span>
    
</div>
    
</div>
    
</body>
    
</html>
