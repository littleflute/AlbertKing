[v0.0.4](https://github.com/littleflute/AlbertKing/edit/master/README.md)
 
[Born Under A Bad Sign (Stax Remasters)](Born Under A Bad Sign [Stax Remasters])

<audio controls id="player"> 
  <source src="https://littleflute.github.io/AlbertKing/Born Under A Bad Sign [Stax Remasters]/01 Young Lust.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
<div id="xd"> 
</div>
<script>
var d = document.getElementById("xd"); 
var html = d.innerHTML; 
html += " acdc<br>Highway To Hell [REMST]<br>CD:<br>";
for(var n=1; n<=19; n++)
{	
 	html += fNewBtn(n);

} 
d.innerHTML = html;

var p = document.getElementById("player");
function f(i)
{
    var s = "https://littleflute.github.io/AlbertKing/Born Under A Bad Sign [Stax Remasters]/";
    if(i==1)
    {
    	s += "01 Born Under a Bad Sign";
    }
    else if(i==2)
    {
    	s += "02 Crosscut Saw";
    }
    else if(i==3)
    {
    	s += "03 Kansas City";
    }
    else
    {
    	if(i<10) 
    	{
    		s += "0";
    	} 
    	s += i;
    	s += "_曲目 ";
    	s += i;
    }
    s += ".mp3";
    
    p.src = s; 
    p.play();
}
function fNewBtn(i)
{
	var rHTML = "";
    rHTML = "<button onclick='f(";
    rHTML += i;
    rHTML += ");'>";
    rHTML += i;
    rHTML += "</button>";
    return rHTML;
}
</script>


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/littleflute/AlbertKing/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/littleflute/AlbertKing/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
