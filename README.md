<style>
body {
  font-family: "CM Handwriting One", Courier New, monospace; 
  background-color: black;
font-size: 22px
}
body::before {
  content: " ";
  display: block;
  position: fixed;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  background: linear-gradient(rgba(18, 16, 16, 0) 50%, rgba(0, 0, 0, 0.25) 50%);
  z-index: 2;
  background-size: 100% 2px, 3px 100%;
  pointer-events: none;
}

#q, button {
  color: red;
  background-color: black;
  border: 1px solid grey;
  font-family: inherit;
}

p, i, b, .count {
  color: red !important;
}

a, .profile .friends .person p, .logout-btn {
  color: red !important;
  text-decoration: underline !important;
}

.container {
  margin: 0 auto 0;
}

.icon {
  display: none;
}

nav, nav .links a {
  color: red;
}

nav .top {
  margin-top: 2px;
  background: none;
  background-color: black;
  border: 2px solid grey;
  border-bottom: none;
}

nav .links {
  background-color: black;
  border: 2px solid grey;
}

body {
  background-image: url(https://m.media-amazon.com/images/M/MV5BZjE0NDJkYWUtYTMxYS00NzExLTkxNjUtOWU4ZTViYWJkMzE3XkEyXkFqcGdeQXVyMTM1ODY5NzMy._V1_.jpg);
  background-attachment: fixed; /* Adjust this based on your preference */
  background-size: cover; /* or contain, or specific dimensions */
  background-repeat: no-repeat;
}

main {
  background: black;
  color: red;
  border-left: 2px solid grey;
  border-right: 2px solid grey;
}

.heading, .url-info {
  color: red !important;
  background: none;
  background-color: black !important;
  border: 2px solid grey !important;
}

.inner {
  color: red !important;
  border: 2px solid grey;
  border-top: none;
}

.profile-info {
  border: 2px solid grey;
}

.profile-info .inner {
  border: none;
}

.friends .inner {
  border-bottom: none;
}

#comments {
  border-bottom: 2px solid grey;
}

.profile .contact, .profile .table-section, .home-actions {
  border: none !important;
}

.profile .contact .f-row:first-of-type {
  margin-top: 0px;
  padding-top: 7px;
}

.profile .blurbs .section h4 {
  color: red !important;
}

.details-table {
  margin: 2px;
}

.details-table, td {
  border: 1px solid grey;
  border-collapse: collapse;
}

td {
  color: red !important;
  background: none;
  background-color: black !important;
}

table.details-table {
  max-width: 98%;
}

.profile h1 {
  font-size: 20px;
}

footer {
  background: black;
  border: 2px solid grey;
}

footer p {
  color red !important;
}

.comments-table {
  border: none;
  border-collapse: collapse;
}

.comment-replies {
  border: 1px solid grey;
  margin: 2px;
}

nav .info {
  background: none;
}
nav .links li .icon{
content: url('https://pixels.crd.co/assets/images/gallery33/352b57c7.gif?v=7212058b');

</style>


<style>
table.comments-table{

display: block;
height: 250px!important;
overflow-y: scroll;

}

</style>
<!-- (c) Layout created by  (https://layouts.spacehey.com/layout?id=29974) -->

<style>


.table-section {
    height: 300px;
    overflow-y: auto;
    border: none!important;
}


.online{
content: url(http://www.coolspacetricks.com/images/myspaceicons/208.gif);
}
</style>


<!-- (c) Layout created by Lily (https://layouts.spacehey.com/layout?id=34798) -->

<style>
/* names of topics, change # */
 :root {
  --topic1: "Me";
  --topic2: "Music";
  --topic3: "Movies/Series";
  --topic4: "Games";
  --topic5: "Books";
  --topic6: "";
}
/* makes original text transparent and moves it off the box */
 .table-section:not(:last-child) .details-table tr td:first-child p {
  color: transparent !important;
  text-shadow: none !important;
  letter-spacing: -100px;
}
/* replaces first topic */
 .table-section:not(:last-child) .details-table tr:nth-child(1) td:first-child p::after {
  content: var(--topic1);
}
/* replaces second topic */
 .table-section:not(:last-child) .details-table tr:nth-child(2) td:first-child p::after {
  content: var(--topic2);
}
/* replaces third topic */
 .table-section:not(:last-child) .details-table tr:nth-child(3) td:first-child p::after {
  content: var(--topic3);
}
/* replaces forth topic */
 .table-section:not(:last-child) .details-table tr:nth-child(4) td:first-child p::after {
  content: var(--topic4);
}
/* replaces fifth topic */
 .table-section:not(:last-child) .details-table tr:nth-child(5) td:first-child p::after {
  content: var(--topic5);
}
/* replaces sixth topic */
 .table-section:not(:last-child) .details-table tr:nth-child(6) td:first-child p::after {
  content: var(--topic6);
}
/* color of text, replace red */
 .details-table tr td:first-child p::after {
  color: red !important;
  letter-spacing: normal !important;
}
</style>
 
<!-- (c) Layout created by Miller , Evelin .﹒ㅤׂ𓈒˖ (https://layouts.spacehey.com/layout?id=84033) -->



<style>
  .profile-pic {
    position: relative;
    width: 189px;
    filter: drop-shadow(0 0 0.25rem gray);
  }

  .profile-pic:after {
    content: "";
    background: url('https://external-media.spacehey.net/media/sp0aJMsEmB2QNy4Nz0CJ_7OSvgd3Bjdj1Em7UbpWuGr4=/https://media.discordapp.net/attachments/1085182478651760661/1166656563549851739/Untitled1482_20231025013616.png?ex=654b4898&is=6538d398&hm=26263ee5ada2b1b153737114adbaa21ea5439ca9465e42ff96c7ba9577f1fbd7&');
    background-size: cover; /* or background-size: contain; */
    position: absolute;
    top: -5%; 
    left: -5%;
    width: 92%;
    height: 110%;
  }
</style>


<style>

.blog-preview {
  display: none;
  grid-area: blog-preview;
}

.blurbs .inner .section h4{
  display: none;
}
.blurbs{margin-top:10px !important;}
      </style>






<style>
/* you dont need to change this top part */
::-moz-selection { 
  color: red;
  background: white;
}

::selection {
  color: [text color];
  background: [highlighter color];
}

</style>

<iframe width="0" height="0" src="YOURURLHERE&;amp;;autoplay=1&;loop=1&;controls=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="" loading="lazy">
</iframe>
