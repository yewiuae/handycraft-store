<template>
    <div class="ps-breadcrumb">
        <div class="ps-container">
            <ul class="breadcrumb">
                <li>
                    <a :href="route('home')">Home</a>
                </li>
                <li>FAQs</li>
            </ul>
        </div>
    </div>
    <div class="ps-container">
        <div class="mt-40 mb-40">
            <div id="app">
                <div class="ps-faqs pt-40 pb-40">
                    <div class="container">
                        <div class="ps-section__header">
                            <h1>Frequently Asked Questions</h1>
                        </div>
                        <div class="ps-section__content">
                            <div class="table-responsive">
                                <table class="table ps-table--faqs">
                                    <tbody>
                                    <tr>
                                        <td rowspan="3" class="heading">
                                            <h4>SHIPPING</h4>
                                        </td>
                                        <td class="question">What Shipping Methods Are Available?</td>
                                        <td>Ex Portland Pitchfork irure mustache. Eutra fap before they sold out literally.
                                            Aliquip ugh bicycle rights actually mlkshk, seitan squid craft beer tempor.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">Do You Ship Internationally?</td>
                                        <td>Hoodie tote bag mixtape tofu. Typewriter jean shorts wolf quinoa, messenger bag
                                            organic freegan cray.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">How Long Will It Take To Get My Package?</td>
                                        <td>Swag slow-carb quinoa VHS typewriter pork belly brunch, paleo single-origin
                                            coffee Wes Anderson. Flexitarian Pitchfork forage, literally paleo fap
                                            pour-over. Wes Anderson Pinterest YOLO fanny pack meggings, deep v XOXO chambray
                                            sustainable slow-carb raw denim church-key fap chillwave Etsy. +1 typewriter
                                            kitsch, American Apparel tofu Banksy Vice.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td colspan="3">
                                            <hr>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td rowspan="2" class="heading">
                                            <h4>PAYMENT</h4>
                                        </td>
                                        <td class="question">What Payment Methods Are Accepted?</td>
                                        <td>Fashion axe DIY jean shorts, swag kale chips meh polaroid kogi butcher Wes
                                            Anderson chambray next level semiotics gentrify yr. Voluptate photo booth fugiat
                                            Vice. Austin sed Williamsburg, ea labore raw denim voluptate cred proident
                                            mixtape excepteur mustache. Twee chia photo booth readymade food truck, hoodie
                                            roof party swag keytar PBR DIY.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">Is Buying On-Line Safe?</td>
                                        <td>Art party authentic freegan semiotics jean shorts chia cred. Neutra Austin roof
                                            party Brooklyn, synth Thundercats swag 8-bit photo booth. Plaid letterpress
                                            leggings craft beer meh ethical Pinterest.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td colspan="3">
                                            <hr>
                                        </td>
                                    </tr>
                                    <tr>
                                        <td rowspan="5" class="heading">
                                            <h4>Order &amp; Returns</h4>
                                        </td>
                                        <td class="question">How do I place an Order?</td>
                                        <td>Keytar cray slow-carb, Godard banh mi salvia pour-over. Slow-carb Odd Future
                                            seitan normcore. Master cleanse American Apparel gentrify flexitarian beard
                                            slow-carb next level. Raw denim polaroid paleo farm-to-table, put a bird on it
                                            lo-fi tattooed Wes Anderson Pinterest letterpress. Fingerstache McSweeney’s
                                            pour-over, letterpress Schlitz photo booth master cleanse bespoke hashtag
                                            chillwave gentrify.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">How Can I Cancel Or Change My Order?</td>
                                        <td>Plaid letterpress leggings craft beer meh ethical Pinterest. Art party authentic
                                            freegan semiotics jean shorts chia cred. Neutra Austin roof party Brooklyn,
                                            synth Thundercats swag 8-bit photo booth.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">Do I need an account to place an order?</td>
                                        <td>Thundercats swag 8-bit photo booth. Plaid letterpress leggings craft beer meh
                                            ethical Pinterest. Twee chia photo booth readymade food truck, hoodie roof party
                                            swag keytar PBR DIY. Cray ugh 3 wolf moon fap, fashion axe irony butcher
                                            cornhole typewriter chambray VHS banjo street art.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">How Do I Track My Order?</td>
                                        <td>Keytar cray slow-carb, Godard banh mi salvia pour-over. Slow-carb @Odd Future
                                            seitan normcore. Master cleanse American Apparel gentrify flexitarian beard
                                            slow-carb next level.
                                        </td>
                                    </tr>
                                    <tr>
                                        <td class="question">How Can I Return a Product?</td>
                                        <td>Kale chips Truffaut Williamsburg, hashtag fixie Pinterest raw denim c hambray
                                            drinking vinegar Carles street art Bushwick gastropub. Wolf Tumblr paleo
                                            church-key. Plaid food truck Echo Park YOLO bitters hella, direct trade
                                            Thundercats leggings quinoa before they sold out. You probably haven’t heard of
                                            them wayfarers authentic umami drinking vinegar Pinterest Cosby sweater,
                                            fingerstache fap High Life.
                                        </td>
                                    </tr>
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
    export default {
        name: "FAQ",
    }
</script>
