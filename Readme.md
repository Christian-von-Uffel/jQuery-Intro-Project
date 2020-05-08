Following along the Traversy Media Youtube jQuery crash course video: https://www.youtube.com/watch?v=3nrLc_JOF7k

## Using jquery

For applications, you want to include the original jQuery file in your codebase, but for inidividal usecases it's ok to load jQery into your browser using a link, also known as via CDN.

Just include this script in the heading of your page:

<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>

Once you've included this script you can just starting writing jQuery code after initilizing with:

<script type="text/javascript">
  your code goes here
</script>



## Using jQuery to create highlights on the page

You can use jQuery to change the background color of elements on pages:

  $('ul#list li:even').css('background', 'yellow');

  $('name of CSS selector').css('background','name of color or hex value here')
