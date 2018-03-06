$('option').on("mousedown", function (e) {
    e.preventDefault();
    jQuery(this).toggleClass('selected');

    jQuery(this).prop('selected', !jQuery(this).prop('selected'));
    var selectBox = $(this).parent("select");
    if (selectBox.val().length > selectBox.attr("data-max")) {
        $(this).toggleClass('selected');
        $(this).prop('selected', !jQuery(this).prop('selected'));
    };
});
