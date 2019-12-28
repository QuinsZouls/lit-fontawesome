# Lit-fontawesome

Icons of Fontawesome for Polymer 3 and LitElement


## Installation

Use the package manager [npm](https://www.npmjs.com/) to install Lit-fontawesome.

```bash
npm install lit-fontawesome
```
In the HTML file, link css of Lit-fontawesome
```html
<link rel="stylesheet" href="node_modules/lit-fontawesome/css/font.css">
```

## Usage with LitElement

```javascript
import { LitElement, html} from 'lit-element';
import Fontawesome from 'lit-fontawesome';

class SomeClass extends LitElement {
 static get styles() {
    return [ Fontawesome ];
 }
 render() {
    return html`
      <div>
         <i class="fas fa-address-card"></i>
      </div>
    `;
  }
}

customElements.define('custom-component', SomeClass );
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)