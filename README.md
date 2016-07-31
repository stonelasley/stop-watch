[![Stories in Ready](https://badge.waffle.io/crodgers/stop-watch.png?label=ready&title=Ready)](https://waffle.io/crodgers/stop-watch)
# &lt;stop-watch&gt;

> A stopwatch custom element using [Polymer](http://www.polymer-project.org/)


## Demo

[Check it live!](http://stonelasley.github.io/stop-watch)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install polymer-stop-watch --save
```

Or [download as ZIP](https://github.com/stonelasley/stop-watch/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/stonelasley/dist/stop-watch.html">
    ```

3. Start using it!

    ```html
    <stop-watch></stop-watch>
    ```

## Options

Attribute       | Options     | Default      | Description
---             | ---         | ---          | ---
`mode`          | *string*    | 'stopwatch'  | Sets the mode 'stopwatch' or 'timer'
`autoStart`     | *bool*      | false        | Starts counting as soon as the element has loaded.
`offset`        | *number*    | 0            | Starts counting at this number. In Milliseconds.


## Methods

Method        | Parameters   | Returns     | Description
---           | ---          | ---         | ---
`unicorn()`   | None.        | Nothing.    | Magic stuff appears.

## Events

Event           | Description
---             | ---
`onWatchStart`  | Triggers when stopwatch is started
`onWatchStop`   | Triggers when stopwatch is stopped;
`onTimerStart`  | Triggers when timer is started
`onTimerStop`   | Triggers when timer is stopped
`onReset`       | Triggers when timer or stopwatch are reset;


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/stonelasley/stop-watch/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)
