# DateTime Picker
Whether you're allowing users to schedule appointments, book a vacation, or schedule a rental online, using a DateTime picker improves their experience and ensures a standardized submission format. Using standard Bootstrap styling and modules, [Solodev](https://www.solodev.com/) provides you a working DateTime Picker to use in your next project.

## Tutorial

For detailed instructions, view Solodev's [Adding a DateTime Picker to your Forms](https://www.solodev.com/blog/web-design/code-examples/adding-a-datetime-picker-to-your-forms.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/euc711xx/).

## HTML

Within the context of your form, a DateTime Picker can be created with the follow HTML:
```
<label class="control-label">Appointment Time</label>
<div class='input-group date' id='datetimepicker1'>
 <input type='text' class="form-control" />
 <span class="input-group-addon">
 <span class="glyphicon glyphicon-calendar"></span>
 </span>
</div>
```

## CSS

CSS for this repository is primarily based on default Bootstrap classes.

## JavaScript

In addition to third-pary resources, you need to initialize the picker:
```
$( document ).ready(function() {
	$('#datetimepicker1').datetimepicker();
});
```

## External Includes

The form includes the following third-party resources:
```
<link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-datetimepicker/4.17.37/css/bootstrap-datetimepicker.min.css">
	
<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script> 
<script type="text/javascript" src="https://cdn.jsdelivr.net/momentjs/2.14.1/moment.min.js"></script> 
<script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script> 
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-datetimepicker/4.17.37/js/bootstrap-datetimepicker.min.js"></script>
```

