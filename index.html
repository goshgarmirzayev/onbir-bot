<html>

<head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
</head>

<body>
    <div class="container text-center " id="area">

    </div>
</body>
<script>

    $(document).ready(function () {
        $.ajax({
            url: 'https://onbir.az/wp-json/wp/v2/posts',
            type: "GET",
            dataType: "json",
            success: function (data) {
                var template = ""
                $.each(data, function (index, element) {
                    console.log(element.link)
                    template +=
                        "<div class=\"row mb-5 mt-5\">\n" +
                        "            <div class=\"col col-md-6 col-lg-6 col-md-offset-4\">\n" +
                        "                <input type=\"text\" class=\"form-control link\"  placeholder=\"Enter link\" value='" + element.link + "'>\n" +
                        "            </div>\n" +
                        "            <div class=\"col col-md-2 col-lg-2\">\n" +
                        "                <input type=\"number\" class=\"form-control count\" placeholder=\"count\">\n" +
                        "            </div>\n" +
                        "            <div class=\"col col-md-4 col-lg-4\">\n" +
                        "                <button id=\"open\" class=\"btn btn-success btn-block open-link\">Open Link </button>\n" +
                        "            </div>\n" +
                        "        </div>"

                })
                $("#area").append(template)
            }
        });
    })
    $(function(){
        $(document).on('click','.open-link', function () {
            console.log($(this).parent())

            let link = $(this).parent().parent().find("input.link").val();
            let count = $(this).parent().parent().find("input.count").val();
            console.log(count)
            for (let i = 0; i < count; i++) {
                window.open(link)
            }
        })
    })
</script>

</html>