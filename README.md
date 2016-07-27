# Demo viewer

Preview components in isolation with documentation, annotations and breakpoint controls.

## Branding

You can change the demo-viewer to look a little more like your own company brand.

On the initial config for the demo-viewer you can pass a path to your logo.

	window.demoViewer({
        modules: [
        	{ logo: '/path/to/logo' },
            { group: 'Media', name: 'Carousel', url: 'media/carousel/', info:
                { readme: 'media/carousel/README.md', template: 'media/carousel/template.html' }
            }
        ]
    });

Also you style the modules on `src/` folder:

* app & core: general app styling
* info-panel: the bottom overlay that shows documentation and code
* module-selector: left part of the navigation including the logo
* size-controls: right part of the navigation where screen sizes can be ajusted

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for [guidelines](CONTRIBUTING.md#guidelines) and [development scripts](CONTRIBUTING.md#scripts).
