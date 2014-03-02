## Sample setup for headless Jasmine testing

This is a sample setup for command-line / headless javascript testing, using Jasmine 2.0 and PhantomJS 1.9+

It's actually the same sample code that ships with Jasmine, tweaked to demonstrate the use of the improved console reporter.

The meat of it is in [SpecRunner.js](https://github.com/qindio/headless-jasmine-sample/tree/master/spec/SpecRunner.js), where the console reporter is wired up.

With this setup you can also see test results through the HTML interface, by accessing the [SpecRunner.html](https://github.com/qindio/headless-jasmine-sample/tree/master/spec/SpecRunner.html) file in your browser.

## Running the suite

Just call phantomjs, passing the path to run-jasmine.js and SpecRunner.html as arguments


```
phantomjs spec/run-jasmine.js spec/SpecRunner.html
```

## Hyping it

Check the blogpost at http://lorenzoplanas.com/blog/20140302-headless-setup-for-jasmine-20
