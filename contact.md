---
layout: page
title: Contact
tagline: CONTACT
bodyClass: contact
permalink: /contact/
navPosition: 4
---

<div class="container">
	<div class="contact">
		<div class="row">
			<div class="col col--4-of-12">
				<div class="contact-info">
					<p><span class="contact-title">HEAD OFFICE</span></p>
					<p>BOX 1306<br />Melville, SK<br />S0A 2P0</p>
					<p style="letter-spacing: 1px;">Tel  306.621.6775<br />Fax 306.782.0204</p>
					<p><a href="mailto:{{site.email}}">{{site.email}}</a></p>
				</div>
			</div>
			<div class="col col--8-of-12">
				<div class="row">
					<div class="col col--12-of-12">
						<p style="text-align: center;">Have any questions? Feel free to leave us a message. We look forward to hearing from you.</p>
					</div>
				</div>
				<div class="inner">
	                <!-- Form Area -->
	                <div class="contact-form">
	                    <!-- Form -->
	                    <form id="contact-us" method="POST" action="//formspree.io/info@narailsafety.com">
	                        <!-- Left Inputs -->
	                        <div class="col col--6-of-12 wow animated slideInLeft" data-wow-delay=".5s">
	                            <!-- Name -->
	                            <input type="text" name="name" id="name" required="required" class="form" placeholder="Name" />
	                            <!-- Email -->
	                            <input type="email" name="_replyto" id="mail" required="required" class="form" placeholder="Email" />
	                        </div><!-- End Left Inputs -->
                            <div class="col col--6-of-12 wow animated slideInLeft" data-wow-delay=".5s">
	                            <!-- Last Name -->
	                            <input type="text" name="last_name" id="last-name" required="required" class="form" placeholder="Last Name" />
	                            <!-- Subject -->
	                            <input type="text" name="phone" id="phone" class="form" placeholder="Phone (optional)" />
	                        </div><!-- End Left Inputs -->
	                        <!-- Right Inputs -->
	                        <div class="col col--12-of-12 wow animated slideInRight" data-wow-delay=".5s">
	                            <!-- Message -->
	                            <textarea name="message" id="message" class="form textarea" placeholder="Message"></textarea>
	                        </div><!-- End Right Inputs -->
	                        <!-- Bottom Submit -->
	                        <div class="relative fullwidth col-xs-12">
	                            <!-- Send Button -->
	                            <button type="submit" value="Send" id="submit" class="form-btn semibold">Send Message</button> 
	                        </div><!-- End Bottom Submit -->
	                        <!-- Clear -->
	                        <div class="clear"></div>
	                    </form>

	                    <!-- Your Mail Message -->
	                    <div class="mail-message-area">
	                        <!-- Message -->
	                        <div class="alert gray-bg mail-message not-visible-message">
	                            <strong>Thank You !</strong> Your email has been delivered.
	                        </div>
	                    </div>

	                </div><!-- End Contact Form Area -->
	            </div><!-- End Inner -->
			</div>
		</div>
	</div>
</div>