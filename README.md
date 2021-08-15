## koodex-persian-date-picker
=============================
<p>
laravel and babakhani persian date picker
</p>

## how to install
<p>
1- composer create-project laravel/lavarel [youeproject name] --prefer-dist
</p>
<p>
(above line will install laravel for more information go to <a href="https://laravel.com/docs/">laravel web site</a>.)
</p>
<p>
2- download (<a href="https://github.com/gitKoodex/koodex-persian-date-picker.git">koodex-persian-date-picker</a> or clone it)
</p>
<p>
3- add content of public folder from downloaded koodex persian date picker to your laravel project
</p>
<p>
(in this folder we have jquery it's from <a href="https://jquery.com/download/">download jquery</a> if you wana you could upgrate it to final release)
</p>
<p>
(persian date picker for javascript from <a href="http://babakhani.github.io/PersianWebToolkit/beta/datepicker/">persian date picker</a> you can upgrate it too.)
</p>
<p>
(bootstrap from <a href="https://mdbootstrap.com/">free version of mdbootstrap</a>. this upgrate able too.)
</p>
<p>
4- in downloaded koodex persian date picker find resource folder replace content file Welcome.blade.php with same in your laravel project
</p>
<p>
5- in downloaded koodex persian date picker find the helper and copy the content to you'r laravel vendor project in this address
</p>

```
(your project address)\vendor\laravel\framework\src\Illuminate\Foundation
```
<p>
ithis is for laravel 8.5.4 if your laravel version is diferente. dont replace helper.php instead of that open helper.php from our git and find //my functions for that press ctrl+f and type //my function then copy all linse bellow this line to the end and paste them at the end of your laravel helper file in this address
</p>

```
(your project address)\vendor\laravel\framework\src\Illuminate\Foundation
```

<p>
6- serve laravel project and in your web browser go to root url of your project
</p>
<p>
on git bash
</p>

```
$ php artisan serve
```

<p>
on google chorme
</p>
<p>
<a href="http://localhost:8000">http://localhost:8000</a>
</p>

## how this work
<p>
this is just :
<p>
1 fresh start laravel 
</p>
<p>
2-fresh start [Persian Datepicker] from (http://babakhani.github.io/PersianWebToolkit/doc/datepicker/index.html)
</p>
<p>
3- add a helper with php class call Jdate
</p>

## thanks
<p>
    1- laravel [laravel](https://github.com/laravel/laravel)
</p>
<p>
    2- babakhani <a href="http://babakhani.github.io/PersianWebToolkit/doc/datepicker/index.html">Persian Date Picker</a>
</p>
<p>
    3- mustafaaloko [mustafaaloko](https://github.com/mustafaaloko/nova-persian-datepicker) for Inspiration
</p>

## without gigy stuff 
i don't add any complex to this and keep it as simple as i could.
but this is under mit licence .so if you prefer some auto job.
go a head.

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more informa
 


