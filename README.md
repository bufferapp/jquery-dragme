jQuery DragMe
=============

A super lightweight jQuery plugin for dragging elements using CSS3 Transforms.
The goal of this plugin is not to be a drop in replacement for jQuery UI's 
draggable, but a minimal plugin to make certain elements draggable on a page, 
i.e. modal windows.

## Usage

```javascript
  $('.my-modal-window').dragMe();
```

Prevent clicking on certain elements from dragging the element.

```javascript
  $('.my-modal-window').dragMe({
    cancel: 'textarea, .button'
  });
```

## Roadmap

- Use requestAnimationFrame for smoother movement

## Contributions

Bug fixes or improvements welcome!
