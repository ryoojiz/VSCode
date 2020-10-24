<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            font-family: Arial, Helvetica, sans-serif;
            margin:0;
            padding: 0;
            font-size: 90%;
            color: #545454;
            line-height: 2em;
        }
        a:link{
            color:black;
            text-decoration: none;
        }
        a:hover{
            color: #999999;
            text-decoration: underline;
        }
        #header{
            display: flex;
            padding: 20px;
            align-items: center;
        }
        #search, #cart{
            flex-grow: 1;
        }
        #logo{
            flex-grow:3;
            text-align: center;
        }
        #cart ul{
            list-style: none;
            margin:0;
            padding: 0;
        }
        #cart{
            text-align: right;
        }
        #cart li{
            display: inline;
            margin-left: 40px;
        }
        #navigation{
            border-top:solid 1px #999999;
            border-bottom:solid 1px #999999;
            text-align: center;
        }
        #navigation ul{
            list-style: none;
            padding: 0;
        }
        #navigation li{
            display: inline;
            margin: 0px 12px;
        }
        #content{
            padding-top: 60px;
            width:1066px;
            margin: 0px auto;
        }
        #breadcrumb{
            font-size: 0.8em;   
            margin-bottom: 40px;
        }
        #breadcrumb ul{
            list-style: none;
            padding: 0;
        }
        #breadcrumb li{
            display: inline;
            margin-right: 8px;
        }
        #article{
            display: flex;
            align-items:flex-start;
        }
        #article-info{
            width: 65%;
            margin-right: 20px;
        }
        #article-price{
            width: 30%;
        }
        #article-price h3{
            margin-top: 0;
        }
        #article-header{
            display: flex;
            align-items:flex-start;
            margin-bottom: 60px;
        }
        #article-img{
            width:40%;
            background-color: #e6e6e6;
            padding: 60px 5px ;
            text-align: center;
            margin-right: 10px;
        }
        #article-img img{
            max-width:80%;
        }
        #article-header-title{
            width:60%;
        }
        #article-header-title h3{
            padding: 0;
            margin-top: 0;
        }
        #download{
           border-top: solid 1px #e6e6e6;
           border-bottom: solid 1px #e6e6e6; 
           padding: 20px 0;
           margin-bottom: 20px;
        }
        .bold-label{
            font-weight: 600;
        }
        #order-form input{
            width:40px;

        }
        #order-form span{
            font-size: 80%;
        }
        #order-form ul{
            list-style: none;
            margin: 0;
            padding: 0;
        }

        #order-form li{
            display:inline;
        }

        #order-form button{
            background-color: darkred;
            color:white;
            border: none;
            padding: 4px 10px;
        }
        .IMAGE_CARD{
            padding: 40px 40px 75px;
            background-color: cadetblue;
        }
        .IMAGE_CARD img{
            max-width: 250px;
            margin: 0px;
            padding: 0px;
        }
        .products-related{
            width: 250px;
            border: 1px #999999 solid;
        }
        #related-container{
            display: flex;
            justify-content: space-evenly;
        }
        #h20{
            font-size: 13px;
        }
        #SPAN_CARD{
            display: flex;
            justify-content: space-between;
        }
        #SPAN_CARD a:link{
            color: blue;
        }
        #SPAN_CARD a:visited{
            color: blue;
        }

    </style>
</head>
<body>
    <div id="header">
        <div id="search">
            <form>
                <div>
                    <input type="text" placeholder="Search HBR Product">
                    <button type="submit">S</button>
                </div>
            </form>
        </div>
        <div id="logo">
                <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/images/stencil/original/nav-hbr-logo_1570720324__61965.original.png" alt="" width="60">
                <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/stencil/38d20a80-df8f-0138-a9b8-0242ac110007/e/33777490-bd12-0137-07b1-0242ac110005/img/custom/nav-store-logo.png" alt="" width="140">
        </div>
        <div id="cart">
            <ul>
                <li><img src="https://cdn11.bigcommerce.com/s-yneuaokjib/stencil/38d20a80-df8f-0138-a9b8-0242ac110007/e/33777490-bd12-0137-07b1-0242ac110005/img/custom/img-cart-0620.png"  alt="" width="28"></li>
                <li><a href="#">Sign In</a></li>
            </ul>
        </div>
    </div><!-- the end of the header -->
    <div id="navigation">
        <ul>
            <li><a href="#">Collections</a></li>
            <li><a href="#">Books</a></li>
            <li><a href="#">Tools</a></li>
            <li><a href="#">Case Studies</a></li>
            <li><a href="#">Articles</a></li>
            <li><a href="#">Magazine Issues</a></li>
            <li><a href="#">Search by Subject</a></li>
            <li><a href="#">HBR Home</a></li>
        </ul>
    </div>
    <div id="content">
        <div id="breadcrumb">
            <ul>
                <li><a href="#">Home</a> > </li>
                <li><a href="#">Articles</a> > </li>
                <li><a href="#">HBR Classic Bestseller</a> > </li>
                <li><a href="#">Leadership & Managing People</a> </li>
            </ul>
        </div>
        <div id="article">
            <div id="article-info">
                <div id="article-header">
                    <div id="article-img">
                        <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/images/stencil/500x500/attribute_rule_images/63333_source_1565536069.jpg?imbypass=on" alt="">
                    </div>
                    <div id="article-header-title">
                        <h3>Leadership That Gets Results (HBR Bestseller)</h3>
                    </div>
                </div>
                <div id="description">
                    <h4>Product Description</h4>
                    <p><span class="bold-label">Publication Date:</span> March 01, 2000</p>
                    <p>A leader's singular job is to get results. But even with all the leadership training programs and "expert" advice available, effective leadership still eludes many people and organizations. One reason, says Daniel Goleman, is that such experts offer advice based on inference, experience, and instinct, not on quantitative data. Now, drawing on research of more than 3,000 executives, Goleman explores which precise leadership behaviors yield positive results. He outlines six distinct leadership styles, each one springing from different components of emotional intelligence. Each style has a distinct effect on the working atmosphere of a company, division, or team, and, in turn, on its financial performance. The styles, by name and brief description alone, will resonate with anyone who leads, is led, or, as is the case with most of us, does both. Coercive leaders demand immediate compliance. Authoritative leaders mobilize people toward a vision. Affiliative leaders create emotional bonds and harmony. Democratic leaders build consensus through participation. Pacesetting leaders expect excellence and self-direction. And coaching leaders develop people for the future. The research indicates that leaders who get the best results don't rely on just one leadership style; they use most of the styles in any given week. Goleman details the types of business situations each style is best suited for, and he explains how leaders who lack one or more of these styles can expand their repertories. He maintains that with practice leaders can switch among leadership styles to produce powerful results, thus turning the art of leadership into a science.</p>
                    <p><span class="bold-label">Product #:</span> R00204-PDF-ENG</p>
                    <p><span class="bold-label">Pages:</span> 13</p>
                    <p><span class="bold-label">Related Topics:</span> Power and influence, Leadership, Management styles</p>
                </div>
            </div>
            <div id="article-price">
                <div>
                    <h3>$8.95</h3>
                    <div id="download">
                        <p>Format</p>
                        <a href="#">PDF</a> <a href="#">Hardcover / Hardcopy (B/W) </a>
                        <p>Languange</p>
                        <a href="#">English</a> <a href="#">Spanish (B/W) </a>
                    </div>
                    <div id="order">
                        <label for="">Quantity</label>
                        <div id="order-form">
                            <ul>
                                <li><input type="text"></li>
                                <li><span>This is a copyrighted PDF. Add copies before sharing with your team.</span></li>
                            </ul>
                             <button type="submit">Add to Cart</button>
                        </div>  
                    </div>
                </div>
            </div>
        </div>
        <h2 id="RELATED_TITLE">Related Products</h2>
        <div id="related-container"> 
            <div class="products-related">
                <div class="IMAGE_CARD">
                    <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/images/stencil/160w/products/16441/154478/10102_500__24242.1599812088.png?c=2" alt="">
                </div>
                <div class="DESCRIPTION_CARD">
                    <span>Press Book</span>
                    <h2>Leadership That Gets Results</h2>
                    <h2 id="h20">(Harvard Business Review Classics)</h2>
                    <span>By Daniel Goleman</span>
                    <div id="SPAN_CARD"><span>$9.99</span><span><a href="#">View Details</a></span></div>
                </div>
            </div>
            <div class="products-related">
                <div class="IMAGE_CARD">
                    <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/images/stencil/160w/products/16441/154478/10102_500__24242.1599812088.png?c=2" alt="">
                </div>
                <div class="DESCRIPTION_CARD">
                    <span>Press Book</span>
                    <h2>Leadership That Gets Results</h2>
                    <h2 id="h20">(Harvard Business Review Classics)</h2>
                    <span>By Daniel Goleman</span>
                    <div id="SPAN_CARD"><span>$9.99</span><span><a href="#">View Details</a></span></div>
                </div>
            </div>
            <div class="products-related">
                <div class="IMAGE_CARD">
                    <img src="https://cdn11.bigcommerce.com/s-yneuaokjib/images/stencil/160w/products/16441/154478/10102_500__24242.1599812088.png?c=2" alt="">
                </div>
                <div class="DESCRIPTION_CARD">
                    <span>Press Book</span>
                    <h2>Leadership That Gets Results</h2>
                    <h2 id="h20">(Harvard Business Review Classics)</h2>
                    <span>By Daniel Goleman</span>
                    <div id="SPAN_CARD"><span>$9.99</span><span><a href="#">View Details</a></span></div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
