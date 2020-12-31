[🔙  Home](./README.md)

# Colors 

## Palette
| Name | Color | Hex | SASS | CSS Custom Prop |
| --- | :---: | --- | --- | --- |
| Royal Dark | ![royal-dark](img/color/royal-dark.svg) | `#48136A` | `$color-royal-dark` | `--color-royal-dark` |
| Royal | ![royal](img/color/royal.svg) | `#774099` | `$color-royal` | `--color-royal` |
| Royal Light | ![royal-light](img/color/royal-light.svg) | `#A86DCA` | `$color-royal-light` | `--color-royal-light` |
| Royal Lightest | ![royal-lightest](img/color/royal-lightest.svg) | `#EAC8FD` | `$color-royal-lightest` | `--color-royal-lightest` |
| Dayglow Dark | ![dayglow-dark](img/color/dayglow-dark.svg) | `#AB0061` | `$color-dayglow-dark` | `--color-dayglow-dark` |
| Dayglow | ![dayglow](img/color/dayglow.svg) | `#E21E8E` | `$color-dayglow` | `--color-dayglow` |
| Dayglow Light | ![dayglow-light](img/color/dayglow-light.svg) | `#FF61BE` | `$color-dayglow-light` | `--color-dayglow-light` |
| Dayglow Lightest | ![dayglow-lightest](img/color/dayglow-lightest.svg) | `#FFF7FC` | `$color-dayglow-lightest` | `--color-dayglow-lightest` |
| Smoky | ![gray-700](img/color/gray-700.svg) | `#1A1A1A` | `$color-gray-700` | `--color-gray-700` |
| Eclipse | ![gray-600](img/color/gray-600.svg) | `#343434` | `$color-gray-600` | `--color-gray-600` |
| Primer | ![gray-500](img/color/gray-500.svg) | `#5B5B5B` | `$color-gray-500` | `--color-gray-500` |
| Granite | ![gray-400](img/color/gray-400.svg) | `#8E8E8E` | `$color-gray-400` | `--color-gray-400` |
| Charcoal | ![gray-300](img/color/gray-300.svg) | `#CBCBCB` | `$color-gray-300` | `--color-gray-300` |
| Eerie | ![gray-200](img/color/gray-200.svg) | `#EAEAEA` | `$color-gray-200` | `--color-gray-200` |
| Heather | ![gray-100](img/color/gray-100.svg) | `#F4F4F4` | `$color-gray-100` | `--color-gray-100` |
| White | ![white](img/color/white.svg) | `#FFFFFF` | `$color-white` | `--color-white` |
| Success | ![success green](img/color/util-success.svg) | `#1DE255` | `$color-util-success` | `--color-util-success` |
| Warning | ![warning green](img/color/util-warning.svg) | `#E7E435` | `$color-util-warning` | `--color-util-warning` |
| Danger | ![danger green](img/color/util-danger.svg) | `#E21D1D` | `$color-util-danger` | `--color-util-danger` |
| Royal Gradient | ![gradient](img/color/grad.svg) | `linear-gradient(135deg, $color-dayglow 0%, $color-royal-dark 100%)` | `$color-grad` | `--color-grad` |

## Color Themes
![light theme](img/color/theme-light.svg)
![dark theme](img/color/theme-dark.svg)

## Partner Colors
<details>
<summary> Palette </summary>

| Name | Color | Hex | SASS | CSS Custom Prop |
| --- | :---: | --- | --- | --- |
| FCM Brand | ![FCM brand blue](img/color/partner-fcm-brand.svg) | `#00457C` | `$color-fcm-brand` | `--color-fcm-brand` |
| FCM Gradient | ![FCM brand gradient](img/color/partner-fcm-grad.svg) | `linear-gradient(135deg, rgba($color-fcm-grad,0.37) 0%, $color-fcm-grad 100%);` | `$color-fcm-grad` | `--color-fcm-grad` |
| CT Brand | ![ct brand blue](img/color/partner-ct-brand.svg) | `#00444F` | `$color-ct-brand` | `--color-ct-brand` |
| CT Gradient | ![ct brand gradient](img/color/partner-ct-grad.svg) | `linear-gradient(135deg, rgba($color-ct-grad,0.37) 0%, $color-ct-grad 100%);` | `$color-ct-grad` | `--color-ct-grad` |
</details>


## SASS Variables

### Usage
`color: $color-gray-500`

### List of Variables
<details>
<summary> SASS / SCSS Variables Snippet </summary>

```
$color-royal:            #774099;
$color-royal-dark:       #48136A;
$color-royal-light:      #A86DCA;  

$color-dayglow:          #E21E8E;  
$color-dayglow-dark:     #AB0061;  
$color-dayglow-light:    #FF61BE;  
$color-dayglow-lightest: #FFF7FC;  

$color-gray-700:         #1A1A1A;  
$color-gray-600:         #343434;  
$color-gray-500:         #5B5B5B;  
$color-gray-400:         #8E8E8E;  
$color-gray-300:         #CBCBCB;  
$color-gray-200:         #EAEAEA;  
$color-gray-100:         #F4F4F4;  

$color-white:            #FFFFFF;

$color-util-success:     #1DE255;
$color-util-warning:     #E7E435;
$color-util-danger:      #E21D1D;

$color-gradient: linear-gradient(135deg, $color-dayglow, $color-royal);

```

</details>


## CSS Custom Properties

### Documentation
- [Can I Use - CSS Custom Properties](https://caniuse.com/#search=custom%20properties)    
- [Mozilla - Custom Properties CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)

### Usage
`color: var(--color-gray-500)`
  
### List of Variables
<details> 
<summary> Custom Properties Variables Snippet </summary>

```
:root {

    --color-royal:            #774099; 
    --color-royal-dark:       #48136A;
    --color-royal-light:      #A86DCA;

    --color-dayglow:          #E21E8E;
    --color-dayglow-dark:     #AB0061;
    --color-dayglow-light:    #FF61BE;
    --color-dayglow-lightest: #FFF7FC;

    --color-gray-600:         #1A1A1A;
    --color-gray-500:         #343434;
    --color-gray-400:         #8E8E8E;
    --color-gray-300:         #CBCBCB;
    --color-gray-200:         #EAEAEA;
    --color-gray-100:         #F4F4F4;

    --color-white:            #FFFFFF;

    --color-util-success:     #1DE255;
    --color-util-warning:     #E7E435;
    --color-util-danger:      #E21D1D;

    --color-gradient: linear-gradient(135deg, --color-dayglow, --color-royal);

}
```
</details>

