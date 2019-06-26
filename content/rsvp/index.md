---
title: RSVP
type: post
featured_image: /images/sneak-peek-catalina-jean-photography-6.jpg
footer_blurb:  "  |  Photos on this page taken by <a href=\"https://catalinajean.com\" target=\"_blank\">Catalina Jean Photography</a>"
draft: true
---
<!-- Reservation -->
<section class="section-reservation bg1-pattern p-t-100 p-b-113">
	<div class="container">
		<div class="row">
			<div class="col-lg-12 p-b-30">
				<div class="t-center">
					<!--<span class="tit2 t-center">
						RSVP
					</span>-->
					<h3 class="tit3 t-center m-b-35 m-t-2">
						Let us know if you're coming
					</h3>
				</div>
				<form class="wrap-form-reservation size22 m-l-r-auto" id="rsvp-form">
					<div class="row">
						<div class="col-md-12">
							<!-- Name -->
							<span class="txt9">
								Name(s)
							</span>
							<div class="wrap-inputname size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<input class="bo-rad-10 sizefull txt10 p-l-20" type="text" name="names" placeholder="Name(s)" />
							</div>
						</div>
					</div>
					<div class="row">
						<div class="col-md-4">
							<!-- People -->
							<span class="txt9">
									Are you coming?
							</span>
							<div class="wrap-inputpeople size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<!-- Select2 -->
								<select class="selection-1" name="rsvp" id="rsvp-select">
									<option>--Select--</option>
									<option>Yes</option>
									<option>No</option>
								</select>
							</div>
						</div>
						<div class="col-md-4" style="display:none;" >
							<!-- Phone -->
							<span class="txt9">
								Phone
							</span>
							<div class="wrap-inputphone size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<input class="bo-rad-10 sizefull txt10 p-l-20" type="text" name="phone" placeholder="Phone" id="phone-input" />
							</div>
						</div>
						<div class="col-md-4" style="display:none;">
							<!-- Email -->
							<span class="txt9">
								Email
							</span>
							<div class="wrap-inputemail size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<input class="bo-rad-10 sizefull txt10 p-l-20" type="text"  name="email" placeholder="Email" id="email-input" />
							</div>
						</div>
					</div>
					<div class="row">
						<div class="col-md-8" style="display:none;" id="dietary-restrictions-div" >
							<!-- Name -->
							<span class="txt9" id="dietary-restrictions-label">
								Dietary Restrictions
							</span>
							<div class="wrap-inputname size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<input class="bo-rad-10 sizefull txt10 p-l-20" type="text" name="dietary" placeholder="Dietary Restrictions" id="dietary-input" />
							</div>
						</div>
						<div class="col-md-4" style="display:none;">
							<!-- People -->
							<span class="txt9">
									Joining for Jetboat ride Friday? <a href="/schedule#jetboats" target="_blank" style="text-decoration: underline;">(more info)</a>
							</span>
							<div class="wrap-inputpeople size12 bo2 bo-rad-10 m-t-3 m-b-23">
								<!-- Select2 -->
								<select class="selection-1" name="jetboat" id="jetboat-select">
									<option>--Select--</option>
									<option>Yes</option>
									<option>No</option>
								</select>
							</div>
						</div>
					</div>
					<div class="wrap-btn-booking flex-c-m m-t-6">
						<!-- Button3 -->
						<button id="submit-form" type="submit" class="btn3 flex-c-m size13 txt11 trans-0-4" style="display:none;">
							RSVP
						</button>
					</div>
				</form>
			</div>
		</div>
		<div class="info-reservation flex-w p-t-80">
			<div class="sizefull w-full-lg p-t-20 p-r-30 p-r-0-md">
				<h4 class="txt5 m-b-18" style="text-align: center">
					Make a mistake?
				</h4>
				<p class="size25" style="margin-left: auto; margin-right: auto;">
					Mistakes happen, we understand. 😃 Just send us a message via the <a href="/contact/">"Questions"</a> page and we'll fix it right up.
				</p>
			</div>
		</div>
	</div>
</section>
<!-- Container Selection1 -->
<div id="dropDownSelect1"></div>
<!-- Modal -->
<div class="modal fade" id="confirmationModal" tabindex="-1" role="dialog" aria-labelledby="confirmationModalLabel" aria-hidden="true" data-backdrop="false">
	<div class="modal-dialog" role="document">
		<div class="modal-content">
		<div class="modal-header">
			<h5 class="modal-title" id="confirmationModalLabel">Success</h5>
		</div>
		<div class="modal-body">
			<p>We've received your RSVP! Thank you so much. 🎊❤✨</p>
		</div>
		<div class="modal-footer">
			<button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
		</div>
		</div>
	</div>
	</div>
<div class="modal fade" id="sendingModal" tabindex="-1" role="dialog" aria-labelledby="sendingModalLabel" aria-hidden="true" data-backdrop="false">
	<div class="modal-dialog" role="document">
		<div class="modal-content">
		<div class="modal-header">
			<h5 class="modal-title" id="sendingModalLabel">Sending....</h5>
		</div>
		<div class="modal-body">
			<p>Sending your RSVP now at about 1/3rd the speed of light... ⚡</p>
		</div>
		</div>
	</div>
</div>