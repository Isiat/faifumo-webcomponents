# &lt;ist-vine&gt;

> Simple web component to create a vine player using [Polymer](http://www.polymer-project.org/).


## Demo

[Check it live!](http://quelicoto.es/polymer/ist-vine/index.html)

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install ist-vine --save
```

Or [download as ZIP](https://github.com/Isiat/ist-vine/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/elements/ist-vine.html">
    ```

3. Start using it!

    ```html
    <ist-vine></ist-vine>
    ```

## Options

Attribute     	| Options     		  	| Default   	| Description
---           	| ---         		  	| ---       	| ---
`v`          	| *string*  (optional)  | 'hJEXhxvbidT' | Id of the vine. Sample: hJEXhxvbidT
`type`        	| *string*  (optional)  | `normal`  	| Type of player. *Values* (normal/postcard)
`autoplaysound` | *boolean* (optional)  | `false`   	| if the sound should start at the beginning. *Values:* (true/false)
`size`          | *int*     (optional)  | `480`     	| Player size, *Values:* (600/480/300)


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

For detailed changelog, check [Releases](https://github.com/Isiat/ist-vine/releases).

## License

[MIT License](http://opensource.org/licenses/MIT)