---
title: "Contact me"
date: 2022-11-20T15:32:55+02:00
description: "Contact Adrian Marcu Freelance Senior Software Engineer" #Good for SEO stuff
draft: false
---

# Ready to collaborate and bring ideas to life?

##### Hit me up! Whether it's brainstorming projects, swapping fresh concepts, or just linking up to grow our circle, I'm game.

<style>
  .contact {
    padding: 2.5rem; /* Consistent padding on all sides */
    max-width: 480px;
    margin: 2rem auto; /* Centered with equal top/bottom spacing */
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    background: #f7f7f7;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.03);
    box-sizing: border-box; /* Ensures padding doesn't push width */
  }

  .form-group {
    margin-bottom: 2rem;
  }

  .label {
    font-size: 1rem;
    font-weight: 600;
    color: #1e1e1e;
    margin-bottom: 0.5rem;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    display: block; /* Ensures full-width alignment */
  }

  .form-control {
    width: 100%;
    padding: 0.9rem 1rem;
    font-size: 1rem;
    color: #1e1e1e;
    background: #fff;
    border: 1px solid #e0e0e0;
    border-radius: 6px;
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.02);
    box-sizing: border-box; /* Keeps padding within width */
  }

  .form-control:focus {
    border-color: #4a4a4a;
    outline: none;
  }

  textarea.form-control {
    resize: vertical;
    min-height: 110px;
  }

  .button {
    background: #1e1e1e;
    color: #fff;
    padding: 0.9rem 2.5rem;
    border: none;
    border-radius: 6px;
    font-size: 1rem;
    font-weight: 500;
    cursor: pointer;
    text-transform: uppercase;
    letter-spacing: 0.5px;
    transition: background 0.2s ease;
    display: block; /* Ensures button aligns properly */
    margin: 0 auto; /* Centers the button */
  }

  .button:hover {
    background: #333333;
  }

  span {
    margin-right: 0.5rem;
    color: #4a4a4a;
  }
  
  .or-divider {
    text-align: center;
    margin: 2.5rem 0;
    position: relative;
  }
  
  .or-divider::before, .or-divider::after {
    content: "";
    display: inline-block;
    width: 40%;
    height: 1px;
    background: #e0e0e0;
    vertical-align: middle;
  }
  
  .or-divider span {
    padding: 0 15px;
    font-weight: 600;
    color: #777;
  }
  
  .calendar-container {
    text-align: center;
    margin: 1.5rem 0;
  }
</style>

<div class="contact">
  <form method="post" action="https://forms.un-static.com/forms/3eec99387bf56de24adf7f477d51be677ceea5cd">
    <div class="form-group">
      <p class="label"><span class="fa fa-user"></span>Name</p>
      <input id="name" name="name" placeholder="Your name" type="text" required class="form-control">
    </div>
    <div class="form-group">
      <p class="label"><span class="fa fa-envelope"></span>Email</p>
      <input id="email" name="email" placeholder="Your email" type="text" required class="form-control">
    </div>
    <div class="form-group">
      <p class="label"><span class="fa fa-message"></span>Message</p>
      <textarea id="message" name="message" placeholder="Your message" required class="form-control"></textarea>
    </div>
    <div class="form-group">
      <button class="button" name="submit" type="submit">Send</button>
    </div>
  </form>

  <div class="or-divider">
    <span>OR</span>
  </div>

  <div class="calendar-container">
    <!-- Google Calendar Appointment Scheduling begin -->
    <link href="https://calendar.google.com/calendar/scheduling-button-script.css" rel="stylesheet">
    <script src="https://calendar.google.com/calendar/scheduling-button-script.js" async></script>
    <script>
    (function() {
      var target = document.currentScript;
      window.addEventListener('load', function() {
        calendar.schedulingButton.load({
          url: 'https://calendar.google.com/calendar/appointments/schedules/AcZssZ2ZGN-5lZU8L0Mff1MyHqT7sv4M6jFdlRtvAXAdFQUXJXJDH7A2m1rsNRIX6m1N4DFbVzk6UuUl?gv=true',
          color: '#1e1e1e',
          label: 'Book an appointment',
          target,
        });
      });
    })();
    </script>
    <!-- end Google Calendar Appointment Scheduling -->
  </div>
</div>