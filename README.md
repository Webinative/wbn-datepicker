# WBN Datepicker
## Simple usage
**HTML**

    <input type="text" 
           id="simple" 
	       name="simple"
	       class="form-control wbn-datepicker" />

**JavaScript**

    $('.wbn-datepicker').datepicker()

## Default value
Use the `value` attribute

**HTML**

	<input type="text" 
	       id="value-specified" 
	       name="value_specified"
	       class="form-control wbn-datepicker"
	       value="2017-03-26" />

## With min and max dates
Use the `data-min` and `data-max` attributes

**HTML**

	<input type="text" 
	       id="value-specified" 
	       name="value_specified"
	       class="form-control wbn-datepicker"
	       data-min="2017-01-15"
	       data-max="2017-04-15" />

## Date range
Use the `data-start-src="from-date-id"` on end-date picker

**HTML**

	<input type="text" id="start-date"
	       name="start_date" 
	       class="form-control wbn-datepicker" />
	<input type="text" id="end-date" 
	       name="end_date"
	       class="form-control wbn-datepicker"
	       data-start-src="start-date" />

## Date range with weekly repeat
Use the `data-repeat="weekly" data-repeat-day="dayOfWeek"` on end-date datepicker

**HTML**

	<input type="text" id="start-date-repeat"
	       name="start_date_repeat" 
	       class="form-control wbn-datepicker" />
	<input type="text" id="end-date-repeat" 
	       name="end_date_repeat"
	       class="form-control wbn-datepicker"
	       data-start-src="start-date-repeat"
	       data-repeat="weekly"
	       data-repeat-day="0" />

## Date range with fortnightly repeat

Use `data-repeat="fortnightly" data-repeat-day="dayOfMonth" data-repeat-start="date"` on end-date picker

**HTML**

	<input type="text"
                 id="start-date-fortnightly-repeat"
                 name="start_date_fortnightly_repeat"
                 class="form-control wbn-datepicker" />
	<input type="text"
                 id="end-date-fortnightly-repeat"
                 name="end_date_fortnightly_repeat"
                 class="form-control wbn-datepicker"
                 data-start-src="start-date-fortnightly-repeat"
                 data-repeat="fortnightly"
                 data-repeat-day="0"
                 data-repeat-start="2017-04-04" />

## Date range with monthly repeat
Use `data-repeat="monthly" data-repeat-day="dayOfMonth"` on end-date datepicker

**HTML**

	<input type="text" id="start-date-repeat"
	       name="start_date_repeat" 
	       class="form-control wbn-datepicker" />
	<input type="text" id="end-date-repeat" 
	       name="end_date_repeat"
	       class="form-control wbn-datepicker"
	       data-start-src="start-date-repeat"
	       data-repeat="weekly"
	       data-repeat-day="0" />

See the [sample.html](https://webinative.github.io/wbn-datepicker/sample.html) file for interactive examples.
