## @font-face and unicode-range
<pre><code>@font-face {
   font-family: 'Noto Color Emoji';
   src: url('../resources/NotoColorEmoji.ttf') format('opentype');
   /* Emoji block ranges */
   unicode-range: U+1F1E6-1F1FF, U+1F300-1F5FF, U+1F600-1F64F, U+1F680-1F6FF, U+2300-23FF, U+2600-26FF, U+2700-27BF;
}

body {
    font-family: 'Noto Color Emoji';
}</code></pre>


note:
    Usage of Google color emoji font in the browser
    unicode-range tells the browser the font only handles these code points

