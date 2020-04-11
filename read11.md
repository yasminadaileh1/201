# EJS

## video 1:
**Introduction:** 
this series of videos will talk about :
* inject a variable using *express*
* loop over an array of values 
* if - else statement 
* layouts
* partials

to start write in the terminal :
touch server.js
npm init -y
npm install --save express body-parser cors **ejs**

in our VS code :
var bodyParser=require('body-parser');
var cors=require('cors');

built in moduels(core moduale for node)
its take two path and join them 

var path= require('path');
var app= express();

app.use(bodyParser());  ---> to configure our app
app.use(cors());

app.set('views', path.join(__dirname, 'views'));

app.set('view engine', 'ejs');


app.get('/', function(req, res){
    res.render('index');
});

app.listen(8000, function (){
    console.log('hello port 8000');
})

and then we will create a new folder name **views** (because the name we put it in the path)
and in this folder we ganna create a new index.ejs file

inside it we will write the following :
<h1> Hello </h1>

in our browser we will see our hello ..

Now how to inject value into our ejs views?

the render takes three parameters which is :
1. veiw (the string of the file)
2. object of local variable
3. callback

app.get('/', function(req, res){
    res.render('index' , {
        foo : 'bar'
    })
});

and in our index file we will change the h1 to :
< h1 > hello <% foo %> < /h1 >

like this in our browser we will see 
 hello bar ..

 How to iterate over a value and array value ?
 app.get('/', function(req, res){
    res.render('index' , {
       people :[
           {name : 'yasmin},
           {name : hussein}
       ] 
    })
});

< ul>
<% for (var person of people) %>
< li><% = person.name %>< /li>
<% }%>
< /ul> -->

in the browser we will see :
* yasmin
* hussein 

If_Else Statement:

<% for (var person of people) %>
<% if(person.name ==='yasmin'){ %>
< li>This is <% = person.name %>< /li>
<% } else { %>
< li>This is not yasmin ! this is <% = person.name %>< /li>
<% } %>
<% } %>
< /ul> -->
 here we will see :
 * this is yasmin
 * this is not yasmin! this is hussein 

 