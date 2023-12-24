$(document).ready(function () {
    $('.review-slick-slider').slick({
      infinite: true,
      speed: 300,
      prevArrow: $("#left-arrow"),
      nextArrow: $("#right-arrow"),
      fade: true,
      swipe: false,
      draggable: false,
      slidesToShow: 1,
      adaptiveHeight: true
    });
    $('.review-slick-slider').on('afterChange', function (event, slick, currentSlide) {
      $('#rev-num').text('0' + (currentSlide + 1))
    });
  });
