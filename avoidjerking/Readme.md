    @mixin  animation{

        -webkit-transform: translate(0px, 0);
        -webkit-transition: -webkit-transform 0.8s ease;
        -moz-transform: translate(0px, 0);
        -moz-transition: -moz-transform 0.8s ease;
        transform: translate(0px, 0);
        transition: -webkit-transform 0.8s ease;
    }


    .customList{
    border:1px;
    @include animation;
     :before{
       content:"";
     } 
    }
