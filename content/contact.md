{
	"title": "Contact Us",
	"date": "2018-10-19T09:00:46-05:00",
	"draft": "false",
	"author": "Reuben L. Lillie",
	"social": true,
	"form": true
}
<form method="POST" action="https://formspree.io/theloopnaz@gmail.com">
	<input type="hidden" name="_subject" value="New Form Submission">
	<input type="text" name="_gotcha" style="display:none" />
	<input type="hidden" name="_next" value="/thanks/" />
	<label for="name">Your name</label>
	<input type="text" name="name" placeholder="First Last" required minlength=3 />
	<label for="email">Your email</label>
	<input name="email" type="email" placeholder="email@domain.com" required pattern="^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$"/>
	<label for="message">Your message</label>
	<textarea name="message" placeholder="Our Church is a missionary church.  It knows no difference between home and foreign fields—in these days, all fields are near.—Phineas Bresee, cofounder of the Church of the Nazarene." required rows=12></textarea>
	<button type="submit">Send</button>
</form>
<aside>
	<section>
		<h2>Connect with Us on Social</h2>
			{{< menu "social" >}}
	</section>	
</aside>
