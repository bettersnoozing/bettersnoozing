<h1 align="center">Hi 👋, I'm Areebah!</h1>
<h3 align="center">A Computer Science and Economics student @ McGill University</h3>

<div className={isVisible ? "animate__animated animate__fadeIn" : ""}>
  <h1 className="home-title">
    hi, i'm <span className="highlight">areebah.</span>
  </h1>
  <h1>
    {`i'm`} <span className="typed-text">{text}</span>
  </h1>
  <p>
    I'm currently studying <b>Computer Science</b> at <b>McGill University</b>,
    with a double minor in Entrepreneurship and Economics.
  </p>
  <p>
    I'm also the <b>Vice President External</b> at the <b>McGill Computer Science Undergraduate Society</b>,
    and am currently working on <b>developing software</b> for the <b>McGill Students' Running Club</b> for McRace 2026.
  </p>
  <p>Want to chat? Don’t hesitate to reach out.</p>
  <button onClick={() => console.log('connect')}>
    Let's Chat <ArrowRightCircle size={25} />
  </button>
</div>


/* default css  */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  color: white;
}

html {
  scroll-behavior: smooth;
  scroll-padding-top: 80px;
}

main, section {
  padding-top: 80px;
}

section{
  padding-top: 80px;
}

body{
  font-weight: 400;
  overflow-x: hidden;
  position: relative;
  background-color: rgb(21, 21, 32) !important;
  color: #fff !important;
  font-family: "Nunito", sans-serif !important;
}

h1, h2, h3, h4, h5, h6 {
  margin: 0;
  padding: 0;
  line-height: normal;
}

.button {
  color: #fff !important;
  font-weight: 700 !important;
  font-size: 1.1rem !important;
  margin-top: 30px !important;
  letter-spacing: 0.8px;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 14px 30px;
  border: 1px solid #fff;
  border-radius: 4px;
  background: transparent;
  transition: 0.3s ease-in-out;
  cursor: pointer;
}

/* fonts  */
.nunito {
  font-family: "Nunito", sans-serif;
  font-optical-sizing: auto;
  font-weight: 40000 !important;
  font-style: normal;
}




