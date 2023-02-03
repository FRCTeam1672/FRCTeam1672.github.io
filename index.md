---
layout: page
---

![Team](/assets/img/team_photo.jpg)

## Who are we?

The Mahwah Robo T-Birds are a team of bright, driven Mahwah High School students that compete in the FIRST Robotics Competition—a worldwide tournament in which high schools from around the world conceive and build their own robot to compete/cooperate in a yearly game. The team was founded in 2005 and has competed in every season since then.

## What is the *FIRST* Robotics Competition?

The *FIRST* Robotics Competition is a yearly competition in which students get six weeks to design, build, test, and practice with a robot to compete against other teams in a challenge that changes every year. Students get assistance from mentors to help them go through the engineering design and manufacturing processes. In previous years, game challenges have included throwing frisbees, shooting foam balls, hanging on bars, and balancing robots on a see-saw in cooperation with other teams.

## Our Sponsors

![Orange & Rockland](/assets/img/sponsors/orange_rockland.png){: .mx-auto.d-block :}
![Shocktech](/assets/img/sponsors/shocktech.png){: .mx-auto.d-block :} ![Aldi](/assets/img/sponsors/aldi.png){: .mx-auto.d-block :}
![Optimum](/assets/img/sponsors/Optimum.jpg) ![OWM](/assets/img/sponsors/OWM.jpg){: .mx-auto.d-block :}
![Inserra](/assets/img/sponsors/InserraSupermarkets.jpg){: .mx-auto.d-block :}
![Mahwah Schools](/assets/img/sponsors/mahwah.png){: .mx-auto.d-block :}

<script>
  // Netlify authentication
  if (window.netlifyIdentity) {
    window.netlifyIdentity.on("init", user => {
      if (!user) {
        window.netlifyIdentity.on("login", () => {
          document.location.href = "/admin/";
        });
      }
    });
  }
</script>
