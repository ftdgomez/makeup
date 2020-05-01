
# Makeup Css

## Beauty enchancer css framework

A scss set of **classes** for fastest development of user interfaces on the web.

### Features

#### Padding & Margin utils (./src/bones/_utils.scss)

Margin or padding top, bottom, left and right in a cool sintaxt. Like bootstrap.

``` scss
    // Examples:
    .pb-1 -> | .pb-1{
             |   padding-bottom: 1em;
             | }

    .px-2 -> | .px-2{
             |    padding-left: 2em;
             |    padding-right: 2em
             | }
```

#### Color theming variables (./src/bones/_colors.scss)

This colors can be edited and that will affect the entire color scheme
of the general theme.

``` scss
    $primary-color: #1994d5 !default;
    $secondary-color: #0e5f8a !default;
    $danger-color: #d31919 !default;
    $success-color: #19d548 !default;
    $warning-color: #d2d519 !default;
    $light-color: #f5f5f5 !default;
    $dark-color: #222 !default;
    $border-color: #e1e1e1 !default;
```

Every color create a class for it self

``` scss
    // for backgrounds
    .bg-#{$color-name}{
        background-color: #{$color-value}
    }
    // for color text
    .color-#{$color-name}{
        color: #{$color-value}
    }
```

--> Text tools, layout tools, misc tools and form tools already working. Pending to document it.
