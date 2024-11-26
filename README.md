# General

## VSCode shorcuts

- **html:5<tab>**: generates a bolerplate related to HTML 5;
- **p*2**: creates 2 paragraphs.


## Important observation

Is important to remember that the tag &lt;header&gt; is different from the tag &lt;head&gt;.


## Meta tags

I created in my site when teacher was talking about meta tags. See the tags that I created:

```
    <meta http-equiv="Content-Type" content="text/html;charset=utf-8">
    <meta name="keywords" content="desenvolvimento, sites, aplicativos, PHP, Ruby, Javascript, Python, React, Cordova, C++">
    <meta name="description" content="Desenvolvedor de sistemas e sites. Utiliza tecnologias como PHP, Ruby, Java, C++, JavaScript, HTML e CSS">
    <meta name="author" content="André de Paula Terceiro">
```

As you can see, the structure is similar;
- have a **content** property;
- maybe have a **name** property; 
- maybe have a **http-equiv** property.


## Lists

You can use the property "**start**" on an &lt;ol&gt; tag to indicate what is the number the list have to start. Example:

<ol start="4">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

You can also use in the &lt;ol&gt; tag the property "**type**", with values "A", "a", "I", "i", "1", "i" as example. Example:

<ol type="I">
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>

### dl, dt and dd

Lists by definition. Examples:

<dl>
    <dt>Sapo</dt>
    <dd>Criatura verde e pegajosa</dd>
    <dt>Coelho<dt>
    <dd>Criatura quente e fofa</dd>
</dl>


## Forms

When you use a tag "**&lt;label&gt;**", you can specify the property "**for**". And in the input field (like a control generated with the tag "**input**"), you must insert a property "**id**" with the same value of the "**for**" property of the label.