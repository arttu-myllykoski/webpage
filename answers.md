## Exercise 1

#### italic
Writing in Markdown is _not_ that hard!

#### bold
I **will** complete these lessons!

#### both bold and italic
"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

#### bold and italic
If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

#### headers
# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six

#### header and italic
#### Colombian Symbolism in _One Hundred Years of Solitude_
Here's some words about the book _One Hundred Years..._.

#### links
[Search for it.](www.google.com)

#### emphasis to link texts
[You're **really, really** going to want to see this.](www.dailykitten.com)

#### links with headings
#### The Latest News from [the BBC](www.bbc.com/news)

#### reference links
Do you want to [see something fun][a fun place]?

Well, do I have [the website for you][another fun place]!

[a fun place]: www.zombo.com
[another fun place]: www.stumbleupon.com

#### imgaes
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

#### images with references
![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png

#### Blockquote
I read this interesting quote the other day:

>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

#### multiparagraph blockquote
>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
>His father told him that story: his father looked at him through a glass: he had a hairy face.
>
>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

#### blockquotes with markdown elements
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

#### Lists
* Flour
* Cheese
* Tomatoes

#### Lists with numbers
1. Cut the cheese
2. Slice the tomatoes
2. Rub the tomatoes in flour

#### Lists with markdown elements
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

#### list nesting
* Calculus
 * A professor
 * Has no hair
 * Often wears green
* Castafiore
 * An opera singer
 * Has white hair
 * Is possibly mentally unwell

 #### tricks to lists and indentation
 1. Cut the cheese

  Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes

  Be careful when holding the knife.
  
  For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

#### Soft break
We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

#### soft breaks in lists
1. Crack three eggs over a bowl.  
 Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
Basically, take the same guidance as above: don't be messy, but if you are, clean it up!


## Exercise 2

#### SMIL
[**Synchronized Multimedia Integration Language SMIL**][smillink] is a [World Wide Web Consortium][wwwc] recomended Extensible Markup Language (XML) to describe multimedia presentations. It defines markup for **timing, layout, animations, visual transitions, and media** embedding among other things. [SMIL][smillink] allows presenting media items such as **text, images, video, audio, links** to other [SMIL][smillink] presentations, and files from multiple web servers. [SMIL][smillink] markup is written in XML, and has similarities to [HTML][htmllink].

[smillink]: https://en.wikipedia.org/wiki/Synchronized_Multimedia_Integration_Language
[htmllink]: https://en.wikipedia.org/wiki/HTML
[wwwc]: https://en.wikipedia.org/wiki/World_Wide_Web_Consortium

#### InkML
[**InkML**][inklink] is an XML-based markup language to describe _"ink"_ data input with an electronic pen or stylus. The recomended specification was published by the [World Wide Web Consortium][wwwc] in September 2011.  
**InkML Toolkit (InkMLTk)** is targeted at providing a suite of tools for working with InkML documents. The toolkit includes the following libraries and tools,

 * [**InkML**][inklink] processor libraries implementing the W3C [**InkML**][inklink] specification
 * Converters library and tools (to and from other ink and image formats)
 * [**InkML**][inklink] viewers as browser plug-ins, and
 * [**InkML**][inklink] applications such as a graphical editor.

[inklink]: https://en.wikipedia.org/wiki/InkML


## Exercise 3

<iframe width="560" height="315" src="https://www.youtube.com/embed/kpwNjdEPz7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

![walter](https://miro.medium.com/max/720/1*rIkmavUeqyRySwlQdA9kKg.webp)


## Exercise 4

public class Person{
  private string name;
  private int age;

  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}





