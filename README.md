# WYSIWYMoo

Is a Markdown What You See Is What You Mean toolbar

Originally inspired by Peter Hellberg's http://code.c7.se/js/markdown_toolbar/,
Ted Devito's jQuery tabby http://teddevito.com/demos/textarea.html and http://softwaremaniacs.org/playground/showdown-highlight/

# Usage

    window.addEvent('domready', function(){
        $$('textarea.markdown').each(function(el){
            new WYSIWYMoo(el);
        });
    });


### Mootools Dependencies
- core/1.3.0:Class
- core/1.3.0:Element.Event
- core/1.3.0:Element.Dimensions
- core/1.3.0:DOMReady
- more/1.3.0:Hash