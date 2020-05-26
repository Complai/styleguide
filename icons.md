# Icons 
_Last updated May 19, 2020_

## Download Icon Set
[👾 Shep Icon Set](https://github.com/Complai/styleguide/raw/master/img/icon/shep-icon-set.zip)

## Sprite Usage
1. [Download Shep Sprite](https://github.com/Complai/styleguide/raw/master/img/icon/_shep-icon-sprite.svg.zip)
2. Unzip, then move `shep-icon-sprite.svg` to `/img` directory
3. Add the following styles to your CSS:
```
svg:not(:root) {
    overflow: hidden;
}

.icon {
    fill: currentColor; /* allows use of `color` property to affect fill */
    width: 1.5rem;
    height: 1.5rem;

    vertical-align: bottom;     

    max-width: 100%;
}
```
4. Reference individual icons like so: 
```
<svg class="icon">
    <use xlink:href="path/to/shep-icon-sprite.svg#icon-name"></use>
</svg>
```


## All Icons

| Icon | Name | Source |
| ---  | ---  | ---    |
| ![](img/icon/add.svg) | `icon-add` | [SVG](img/icon/add.svg) |
| ![](img/icon/air.svg) | `icon-air` | [SVG](img/icon/air.svg) |
| ![](img/icon/alert-success.svg) | `icon-alert-success` | [SVG](img/icon/alert-success.svg) |
| ![](img/icon/alert-warn.svg) | `icon-alert-warn` | [SVG](img/icon/alert-warn.svg) |
| ![](img/icon/back.svg) | `icon-back` | [SVG](img/icon/back.svg) |
| ![](img/icon/bonus.svg) | `icon-bonus` | [SVG](img/icon/bonus.svg) |
| ![](img/icon/cancel.svg) | `icon-cancel` | [SVG](img/icon/cancel.svg) |
| ![](img/icon/car.svg) | `icon-car` | [SVG](img/icon/car.svg) |
| ![](img/icon/caret-down.svg) | `icon-caret-down` | [SVG](img/icon/caret-down.svg) |
| ![](img/icon/check.svg) | `icon-check` | [SVG](img/icon/check.svg) |
| ![](img/icon/close.svg) | `icon-close` | [SVG](img/icon/close.svg) |
| ![](img/icon/coffee.svg) | `icon-coffee` | [SVG](img/icon/coffee.svg) |
| ![](img/icon/data.svg) | `icon-data` | [SVG](img/icon/data.svg) |
| ![](img/icon/delete.svg) | `icon-delete` | [SVG](img/icon/delete.svg) |
| ![](img/icon/early.svg) | `icon-early` | [SVG](img/icon/early.svg) |
| ![](img/icon/edit.svg) | `icon-edit` | [SVG](img/icon/edit.svg) |
| ![](img/icon/fitness.svg) | `icon-fitness` | [SVG](img/icon/fitness.svg) |
| ![](img/icon/forward.svg) | `icon-forward` | [SVG](img/icon/forward.svg) |
| ![](img/icon/handle.svg) | `icon-handle` | [SVG](img/icon/handle.svg) |
| ![](img/icon/images.svg) | `icon-images` | [SVG](img/icon/images.svg) |
| ![](img/icon/info.svg) | `icon-info` | [SVG](img/icon/info.svg) |
| ![](img/icon/late.svg) | `icon-late` | [SVG](img/icon/late.svg) |
| ![](img/icon/laundry.svg) | `icon-laundry` | [SVG](img/icon/laundry.svg) |
| ![](img/icon/list.svg) | `icon-list` | [SVG](img/icon/list.svg) |
| ![](img/icon/location.svg) | `icon-location` | [SVG](img/icon/location.svg) |
| ![](img/icon/message.svg) | `icon-message` | [SVG](img/icon/message.svg) |
| ![](img/icon/money.svg) | `icon-money` | [SVG](img/icon/money.svg) |
| ![](img/icon/more.svg) | `icon-more` | [SVG](img/icon/more.svg) |
| ![](img/icon/pin-exclusive.svg) | `icon-pin-exclusive` | [SVG](img/icon/pin-exclusive.svg) |
| ![](img/icon/pin-preferred.svg) | `icon-pin-preferred` | [SVG](img/icon/pin-preferred.svg) |
| ![](img/icon/pin-smartstay.svg) | `icon-smartstay` | [SVG](img/icon/smartstay.svg) |
| ![](img/icon/restaurant.svg) | `icon-restaurant` | [SVG](img/icon/restaurant.svg) |
| ![](img/icon/shuttle.svg) | `icon-shuttle` | [SVG](img/icon/shuttle.svg) |
| ![](img/icon/star-outline.svg) | `icon-star-outline` | [SVG](img/icon/star-outline.svg) |
| ![](img/icon/star.svg) | `icon-star` | [SVG](img/icon/star.svg) |
| ![](img/icon/upgrade.svg) | `icon-upgrade` | [SVG](img/icon/upgrade.svg) |
| ![](img/icon/wifi.svg) | `icon-wifi` | [SVG](img/icon/wifi.svg) |
| ![](img/icon/workstation.svg) | `icon-workstation` | [SVG](img/icon/workstation.svg) |

