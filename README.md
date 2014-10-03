jQuery-Touch-Events
===================

Zepto's touch events port for jQuery

Refer http://zeptojs.com/#Touch events for documentation. Tested with emulator in Chrome.

All tests passed.

Example : 
  
    $(document).on('tap', function () {
        console.log('tap');
    });
    $(document).on('singleTap', function () {
        console.log('singleTap');
    });
    $(document).on('doubleTap', function () {
        console.log('doubleTap');
    });
    $(document).on('longTap', function () {
        console.log('longTap ');
    });
    $(document).on('swipe', function () {
        console.log('swipe');
    });
    $(document).on('swipeLeft', function () {
        console.log('swipeLeft');
    });
    $(document).on('swipeRight', function () {
        console.log('swipeRight');
    });
    $(document).on('swipeUp', function () {
        console.log('swipeUp ');
    });
    $(document).on('swipeDown', function () {
        console.log('swipeDown');
    });
