# Content

This document contains content (mostly HTML) used in the Blackbaud onMessage-based *Schools United* site. If you're looking for images or other stuff and not code snippets like you see below, they're probably in the folder called `Assets`.

## Master Layout(s)

### Header Logo
```
<div class="header-logo"><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/216313/su-wordmark-blue.svg" alt="Schools United"></div>
```

### Footer Link Column 1
```
<!--uncomment to add links
<ul>
<li>Link</li>
<li>Link</li>
<li>Link</li>
</ul>-->
```

### Footer Link Column 2
```
<!-- uncomment to add links & move copyright info to right column (remove inline text center style)
<ul>
<li>Link</li>
<li>Link</li>
<li>Link</li>
</ul>-->
<div style="text-align:center">© Schools United 2019</div>
```

### Footer Link Column 3
```
<!-- uncomment to add links & add copyright info below link list
<ul>
<li>Link</li>
</ul>-->
```

### Footer Script Injection
```
<script>
head.ready(function() {
console.log('js in bb is a go');  
$('head').append('<link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.7.1/css/all.css" integrity="sha384-6jHF7Z3XI3fF4XZixAuSu0gGKrXwoX/w3uFPxC56OtjChio7wtTGJWRW53Nhx6Ev" crossorigin="anonymous">')
});
</script>
```

## Page Content

### Hero Text (animated with CSS)
```
<div class="hero-text"><h1 class="sentence">Uniting&nbsp;<div class="slidingVertical"><span>Schools</span> <span>Leaders</span> <span>Educators</span> <span>Believers</span></div>
</h1></div>
```

### Hero Button
```
<button id="hero-button"><i class="fal fa-handshake"></i>&nbsp;Join the Community</button>
```

### Text Section 1
```
<div class="h2-container">
<h2>Our Mission</h2>
</div>
<h3>Furthering His Kingdom</h3>
<div class="p-text">Thundercats austin kickstarter single-origin coffee, hashtag XOXO venmo 3 wolf moon godard tumblr keytar locavore. Pok pok chillwave portland, affogato dreamcatcher listicle slow-carb next level tacos viral swag woke tumeric chambray. Everyday carry raclette tilde shabby chic raw denim small batch. Stumptown iceland banh mi microdosing, heirloom kogi man bun knausgaard hashtag quinoa cornhole artisan tumeric four dollar toast meh. Gluten-free williamsburg activated charcoal, schlitz ugh narwhal tote bag yuccie.</div>
```

### Text Section 2
```
<div class="h2-container">
<h2>Our Community</h2>
</div>
<h3>Unity of Believers</h3>
<div class="p-text">Truffaut yr fam occupy humblebrag chartreuse +1 raw denim. Activated charcoal jean shorts woke godard selvage enamel pin chia. Master cleanse single-origin coffee 90's meditation lumbersexual. Taxidermy kitsch man braid, raw denim aesthetic normcore DIY mumblecore banjo messenger bag activated charcoal tumblr. Jianbing ennui vape, next level knausgaard activated charcoal umami vegan quinoa freegan tbh hoodie celiac. XOXO twee stumptown street art. Man bun four dollar toast hexagon single-origin coffee salvia tumeric authentic venmo biodiesel crucifix vape wayfarers yuccie distillery quinoa.</div>
```

### Text Section 2 Buttons
```
<div class="text-2-btns"><button id="text-2-button-1"><i class="fal fa-handshake"></i>&nbsp;Join the Community</button><button id="text-2-button-2"><i class="fal fa-info-circle"></i>&nbsp;Find out more</button></div>
```

### Event Section Text
```
<div class="h2-container">
<h2>Featured Event</h2>
</div>
<h3 style="text-align: center;">Professional Development Day 2019</h3>
<br />Flannel ennui paleo seitan lumbersexual vape. Tofu brooklyn migas stumptown. Taxidermy air plant church-key, offal palo santo salvia subway tile craft beer venmo. Unicorn +1 gluten-free sustainable.
```

### Event Section Buttons
```
<div class="event-btns"><button id="event-button-1"><i class="fal fa-ticket-alt"></i>&nbsp;Register Now</button><button id="event-button-2"><i class="fal fa-info-circle"></i>&nbsp;Find out more</button></div>
```

### Email Section Text
```
<h3>Get Updates from Schools United</h3>
```

### Email Section Form
```
<form><input  type="text" name="email" maxlength="80" size="30"><button><i class="fal fa-paper-plane"></i>&nbsp;Submit</button></form
```
