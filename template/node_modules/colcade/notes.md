<!-- append -->
<!-- prepend -->

<!-- html init -->

munge

    // munge
    if ( value == 'true' ) {
      value = true;
    } else if ( value == 'false' ) {
      value = false;
    } else if ( value && value.match(/^\d*\.?\d*$/) ) {
      value = parseFloat( value );
    }

tests
