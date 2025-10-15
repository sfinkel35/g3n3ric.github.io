### Team Roles & Members
- Project Manager: [Graham Parker](https://homework2-130659619927.us-central1.run.app/home)
- Artifacts Manager: [James Chen](/people/jchen.md)
- Expert/Customer Liaison: Sean Finkel
- Security/Assurance Manager: [Mohsin Hossain](/people/mHossain.md)
- Project Facilitator: [Shane Carr](/people/sCarr.md)

### Photos
<section class="team">
  <style>
    .team {
      --card-gap: 14px;
      --radius: 10px;
      --shadow: 0 6px 18px rgba(0,0,0,.08);
      max-width: 1000px;
      margin: 16px auto;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, "Noto Sans", sans-serif;
    }

    .team-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      grid-auto-rows: auto;
      gap: var(--card-gap);
    }

    .member {
      background: #111418;
      border: 1px solid rgba(255,255,255,.08);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 14px;
      text-align: center;
      color: #eaecef;
    }

    .member img {
      width: 100%;
      aspect-ratio: 1 / 1;
      object-fit: cover;
      border-radius: 8px;
      display: block;
    }

    .member figcaption {
      margin-top: 10px;
      font-size: 0.95rem;
      font-weight: 600;
      letter-spacing: .2px;
    }

    @media (max-width: 640px) {
      .team-grid { grid-template-columns: 1fr; }
      .leader { grid-column: auto; }
    }
  </style>

  <div class="team-grid">
    <figure class="member">
      <img src="images/grahamParker.jpg" alt="Graham Parker">
      <figcaption>Graham Parker</figcaption>
    </figure>
    <figure class="member">
      <img src="images/jamesChen.png" alt="James Chen">
      <figcaption>James Chen</figcaption>
    </figure>
    <!-- <figure class="member">
      <img src="images/sean-finkel.jpg" alt="Sean Finkel">
      <figcaption>Sean Finkel</figcaption>
    </figure> -->
    <figure class="member">
      <img src="images/mohsinHossain.png" alt="Mohsin Hossain">
      <figcaption>Mohsin Hossain</figcaption>
    </figure>
    <figure class="member">
      <img src="images/shaneCarr.png" alt="Shane Carr">
      <figcaption>Shane Carr</figcaption>
    </figure>
  </div>
</section>


### Project Background
The Lane Management System (LMS) is a driver assistance technology that is designed to enhance vehicle safety by detecting lane markings, monitoring the vehicles position within its lane, and issue warnings or corrective measures when needed. Using a combination of image processing, camera sensors, and estimating the vehicle state, the LMS can monitor a system of information. The LMS can identify lane boundaries, calculate the vehicles later position, and predict possible deviations. The system will be comprised of 3 key functions. The Lane Departure Warning System (LDWS), the Lane Centering System (LCS), and the Lane Keeping System (LKS). The project also accounts for real world challenges such as curved roads, missing markings, and intentional lane changes, while emphasizing the importance of cybersecurity as steering and speed control become increasingly automated.

### Project Description
The Lane Management System must be capable of performing 3 major tasks during its standard operation. Firstly, it must utilize its LDWS feature to warn drivers who are leaving their lane. It must also utilize its LCS feature to alert drivers who are off-center in their lane. Additionally, it must utilize its LKS feature to intervene when the user is dangerously veering out of major road lanes. The system utilizes a set of cameras and image processing subsystems to only activate when necessary. The system will also be rigorously tested against edge cases. The system will be capable of withholding activation when no major problems arise, and it will be capable of alerting the user when major subsystems are unavailable. Lastly, it will not take control away from drivers that continue to take action against the activated LKS subsystem.

### Friend Links
- [CSE 435 course website](https://cse.msu.edu/~cse435/)
- [Professor Betty H.C. Cheng's profile](https://www.cse.msu.edu/~chengb/)
