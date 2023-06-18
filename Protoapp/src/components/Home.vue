<template>
  <div class="content1">
    <div class="upper-left-div">
      <h1>Protoapp</h1>
      <h2>
        Our landing page template works on all devices, so you only have to set
        it up once, and get beautiful results forever.
      </h2>
      <button class="button">Get Started</button>
    </div>
  </div>

  <div class="content2">
    <hr class="divider" />
    <img src="./assets/badge.play-store.svg" alt="badge.play-store" />
    <img src="./assets/badge.app-store.svg" alt="badge.app-store.svg" />
    <hr class="divider" />
  </div>

  <div class="content3">
    <h1>Meet Protoapp</h1>
    <h2>
      The app lorem ipsum is common placehodler text used to demonstrate the
      graphic elements of a document or visual presentation.
    </h2>
  </div>

  <div class="content4">
    <div class="left-div">
      <h1>Discover</h1>
      <h2>
        Get information on using these guildelines whenever you are using
        therefore they have the same style and quality.
      </h2>
    </div>
    <div class="right-div">
      <img src="./assets/product-search.svg" alt="product-search" />
    </div>
  </div>

  <div class="content5">
    <div class="left-div">
      <img src="./assets/product-smartphone.svg" alt="product-smartphone" />
    </div>
    <div class="right-div">
      <h1>Augmented</h1>
      <h2>
        Word salad often arouses curiosity due to its seemingly intelligent and
        tasteful playon words.
      </h2>
    </div>
  </div>

  <div class="content6">
    <div class="left-div">
      <h1>Endless Possibilities</h1>
      <h2>
        Management Systems shouldn't be a bore. Run out of words? heres some
        lorem ipsum: Lorem ipsum dolor sit amet
      </h2>
    </div>
    <div class="right-div">
      <img src="./assets/product-work.svg" alt="product-work" />
    </div>
  </div>

  <div class="content7">
    <div class="upper-div">
      <h1>Deep dive. Ready?</h1>
      <h2>So are we. Unless. You're Not. Word filler</h2>
    </div>
    <div class="lower-div">
      <img src="./assets/badge.play-store.svg" alt="badge.play-store" /><img
        src="./assets/badge.app-store.svg"
        alt="badge.app-store.svg"
      />
    </div>
  </div>

  <div class="content8">
    <div>
      <h1>Last Call to Action</h1>
      <h2>Another section content goes here</h2>
    </div>
  </div>

  <div class="content9">
    <div class="content9.left-div">
      <div class="box1">
        <div class="left-inner-box">
          <img src="./assets/badge.laravel-mix.svg" alt="badge.laravel-mix" />
          
          <div class="small-container">AUTOMATION</div>
        
        </div>
        <div class="right-inner-box">
          <h2>ROLL OUT</h2>
          <h1>Automatic<br />Prototyping</h1>
          <h2>
            Webpack is the most powerful and flexible asset compilation tool
            available today. With that power, however, comes a certain of
            complexity
          </h2>
        </div>
      </div>
    </div>

    <div class="content9.right-div">
      <div class="box2">
        <div class="left-inner-box">
          <img src="./assets/badge.how-to-read-code.svg" alt="badge.how-to-read-code" />
          
          <div class="small-container">SIMPLICITY</div>
        
        </div>
        <div class="right-inner-box">
          <h2>SIP COFFEE</h2>
          <h1>Complexity<br />Simplified</h1>
          <h2>
            I know too many backend developers who are stifled by one glaring
            phobia: CSS. How do you construct a layout when nothing lines up?
          </h2>
        </div>
      </div>
    </div>
  </div>
  <div class="content10">
    <div class="footer">
      <div class="footer-left">
        <img alt="Protoapp logo" class="logo" src="./assets/logo1.svg" />
      </div>
      <div class="footer-right">
        <h1>Protoapp</h1>
        <h2>Camp One Inc, LLC</h2>
        <h3>
          Que ad Lorem ipsum dolor sit amet, consectetur adipisicing elit. Qui
          reprehenderit rerum ullam necessitatibus, at ab quae expedita illo,
          nobis ipsum maxime assumenda dolorum quo ut deleniti possimus.
          Eveniet, voluptatem provident.
        </h3>
      </div>
    </div>
    <div class="footer-bottom">
      <h3>© 2019 Protoapp. All rights reserved.</h3>
    </div>
  </div>
</template>

<style>

  button {
    display: inline-block;
    padding: 0.3rem 1rem;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 4px;
    font-size: 18px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  button:hover {
    background-color: #2248e2;
  }
  .upper-left-div {
    float: left;
    padding: 0 28rem 0 0;
  }
  .left-div {
    float: left;
    text-align: right;
    padding: 0 2rem 0 8rem;
    width: 100%;
  }
  .right-div {
    float: right;
    text-align: left;
width: 100%;
    padding: 0 8rem 0 0rem;
  }
  .divider {
    border: none;
    border-top: 1px solid #ccc;
    margin: 1rem 0;
  }

  .upper-div {
    flex-direction: column;
    display: flex;
    margin-top: 2rem;
    padding: 0.3rem;
    margin-bottom: 2rem;
  }
  .lower-div {
    flex-direction: row;
    display: flex;
    margin-top: 2rem;
    padding: 0.3rem;
    margin-bottom: 2rem;
  }

  .content1 {
    display: flex;
    margin-top: 10rem;
    padding: 0.3rem;
    margin-bottom: 10rem;
  }
  .content1 h1 {
    font-weight: 200;
    font-size: 6rem;
  }

  .content2 {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 0.3rem;
    margin-bottom: 10rem;
  }
  .content2 img {
    margin: 1rem;
  }

  .content3 {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    /* margin-bottom: 10rem; */
    padding: 1rem 15rem 1rem 15rem;
  }

  .content4 {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    text-align: right;
    margin-bottom: 10rem;
    padding: 0.3rem;
  }
  .content4 img {
    width: 100%; /* Adjust the width to your desired size */
    height: 600px; /* Adjust the height to your desired size */
  }
  .content5 {
    display: flex;
    flex-direction: row;
    text-align: left;
    padding: 0.3rem;
    margin-bottom: 10rem;
  }
  .content5 img {
 width: 100%; /* Adjust the width to your desired size */
    height: 600px; /* Adjust the height to your desired size */
    /* padding: 0.3rem
; */
  }
  .content6 {
    display: flex;
    flex-direction: row;
    text-align: right;
    padding: 0.3rem;
    margin-bottom: 10rem;
  }
  .content6 img {
     width: 100%; /* Adjust the width to your desired size */
    height: 600px; /* Adjust the height to your desired size */
    margin-bottom: 10rem;
  }
  .content7 {
    display: flex;

    margin-bottom: 10rem;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-color: #2248e2;
    padding: 0.3rem;
  }
  .content7 img {
    /* width: 100px; /* Adjust the image size as needed */
    /* height: 100px;  */
    padding: 0.3rem;
  }

  .content7 h1 {
    color: #ffffff;
  }
  .content7 h2 {
    color: #ffffff;
  }

  .content8 {
    display: flex;
    margin-bottom: 10rem;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;

    padding: 0.3rem;
  }

  .content9 {
    display: flex;

    flex-direction: row;
    margin-bottom: 10rem;

    padding: 0.3rem;
  }

  .content9.left-div {
    display: flex;
    flex-direction: row;
    float: left;

    margin: 0;
  }
  .content9.right-div {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    float: right;
    text-align: left;

    margin: 0;
  }
  .content9 h1 {
    margin: 0;
    font-size: 1.2rem;
    font-weight: bold;
    color: #ffffff;
  }
  .content9 h2 {
    margin: 0;
    font-size: 1rem;
    color: #ffffff;
  }
  .content10 {
    display: flex;
    flex-direction: column;
    background-color: #343a40;
    padding-left: 5rem;
  }
  .content10 img {
    height: 50px;
  }
  .content10 h1 {
    font-size: 15px;
    color: #ffffff;
  }
  .content10 h2 {
    font-size: 15px;
    font-weight: normal;
    color: #ffffff;
  }
  .content10 h3 {
    font-size: 12px;
    font-weight: normal;
    color: #ffffff;
  }

    .small-container {
  height: 40px;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 1rem 0 0 0;
  color: #ffffff;
  background: rgba(0, 0, 0, 0.5);
  border-radius: 20px;
}

  .footer {
    margin: 2rem 0 2rem 0;
    display: flex;
    flex-direction: row;
  }

  .footer-right {
    padding: 0 40rem 0 0;
  }
  .footer-bottom {
    margin-bottom: 2rem;
  }

  .box1 {
    background-color: #ffc107;
    display: flex;
    flex-direction: row;
    /* padding: 5rem; */
    margin: 3rem;
    border-radius: 20px;
  }
  .box2 {
    background-color: #17a2b8;
    display: flex;
    flex-direction: row;
    /* padding: 5rem; */
    margin: 3rem;
    border-radius: 20px;
  }
  .left-inner-box {
    display: flex;
    flex-direction: column;
    float: center;
    justify-content: center;
    align-items: center;
    text-align: left;
    /* max-width: 50%; */
    padding: 2rem;
    /* margin: 1rem; */
    /* width: 150; */
  }
  .right-inner-box {
    display: flex;
    flex-direction: column;
    /* float: center; */
    /* justify-content: center; */
    /* align-items: center; */
    text-align: left;
    /* max-width: 50%; */
    padding: 2rem;
    margin: 0;
  }
  .box4 {
    display: flex;
    flex-direction: column;
    float: center;
    text-align: left;
    /* max-width: 50%; */
    padding: 0.3rem;
  }

</style>
