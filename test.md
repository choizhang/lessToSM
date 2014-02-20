#aaa
    Alert.prototype.close = function (e) {
        var $this    = $(this)
        var selector = $this.attr('data-target')
    
        if (!selector) {
          selector = $this.attr('href')
          selector = selector && selector.replace(/.*(?=#[^\s]*$)/, '') // strip for ie7
        }

    var $parent = $(selector)

    var d=a(this),e=d.attr("data-target");e||(e=d.attr("href"),e=e&&e.replace(/.*(?=#[^\s]*$)/,""));var f=a(e);

   var Carousel = function (element, options) {
       this.$element    = $(element)
       this.$indicators = this.$element.find('.carousel-indicators')
       this.options     = options
       this.paused      =
       this.sliding     =
       this.interval    =
       this.$active     =
       this.$items      = null