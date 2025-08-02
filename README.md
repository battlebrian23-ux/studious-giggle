<form 
  action="https://formsubmit.co/YOUR_EMAIL@example.com" 
  method="POST" 
  className="space-y-4"
>
  <input type="hidden" name="_captcha" value="false" />
  <input type="hidden" name="_template" value="box" />

  <input
    type="text"
    name="name"
    placeholder="Your Name"
    required
    className="w-full border border-gray-300 rounded-xl p-3"
  />
  <input
    type="email"
    name="email"
    placeholder="Your Email"
    required
    className="w-full border border-gray-300 rounded-xl p-3"
  />
  <textarea
    name="message"
    placeholder="Tell us about your cleaning needs..."
    required
    className="w-full border border-gray-300 rounded-xl p-3 h-32"
  ></textarea>
  <Button className="w-full bg-blue-600 hover:bg-blue-700 text-white">
    Submit Request
  </Button>
</form> studious-giggle
