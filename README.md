accordion
=========

Trigger showing and hiding of content.

Used in conjunction with [nib-components/accordion](https://github.com/nib-components/accordion) javascript component.

    component install nib-styles/accordion

##Example markup

    <div class="accordion is-closed js-accordion">
      <div class="accordion__trigger js-trigger">Click me</div>
      <div class="accordion__body js-body">
        <div class="accordion__body-padding">
          Show and hide me
        </div>
      </div>
    </div>

## Build (dev)

    sass index.scss > index.css
    component build --dev


##Changelog

###v1.0.0

 - Refreshed styles to match current nib design direction