# Bootsrap Modal

## Template

### Modal

```html
<div id="TARGET_MODAL" class="modal fade" tabindex="-1">
  <div class="modal-dialog modal-md">
    <div class="modal-content">
      <div class="modal-header">
        <button type="button" class="close" data-dismiss="modal">&times;</button>
        <h5 class="modal-title"> ...title... </h5>
      </div>
      <div class="modal-body">
        ...body...
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-link" data-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary" id="">Save</button>
      </div>
    </div>
  </div>
</div>
```

### Button that triggers it

```html
<button type="button" data-toggle="modal" data-target="#TARGET_MODAL"> Modal Button </button>
```

### From JS

#### Open Modal
```js
$("#TARGET_MODAL").modal('hide');
```

#### Close Modal
```js
$('#TARGET_MODAL').modal('show');
```
