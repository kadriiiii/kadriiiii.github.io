<style>
  .button1 {
    background-color: #F8F9F9; // light gray
    color: #2C0735; // Glia black purple
    border: 2px solid #7C19DD; //Glia purple
    font-size: 16px;
    border-radius: 14px;
    padding: 10px 24px;
    cursor: pointer;
    transition: all 0.3s ease;
    }
  .button1:hover {
    color: #F8F9F9; //light gray
    background-color: #C04CFD; // Glia orchid
    border-color: #C04CFD; // Glia orchid
    }
  .button1:active {
    color: #F8F9F9; //light gray
    background-color: #7C19DD; // Glia purple
    border-color: ##7C19DD; // Glia purple
    }
  .button1:focus {
    outline: none;
    box-shadow: 0 0 0 5px #EA7AF4; // Glia light violet
    }
  .footer {
    padding-top: 20px;
    padding-bottom: 30px;
    margin-top: 40px;
    font-size: 13px;
    color: #aaa;
    background: transparent url(../images/hr.png) 0 0 no-repeat;
  }
</style>


<script src="//api.glia.com/salemove_integration.js"></script>
    
<div id="title">
  <h1>Meltdown</h1>
</div>         
        
<div id="meltdown_pic">
  <img src="../img/meltdown.png" alt="Example of NM" />
  <br>
  Source: <a href="https://xkcd.com/2163/" target="_blank">xkcd</a>
</div>

<br>        
<div id="contact-us" align="center">
  <a data-sm-show-media-selection-on="click" href="javascript:void(0);" style="display: block;">
    <h3>
      Contact us!
    </h3>
  </a>
</div>
        
<div align="center" id="call-visualizer">
  <button
      class="omnibrowse-code-button"
      onclick="document.body.appendChild(document.createElement('sm-visitor-code'))">
        Get CoBrowsing code
  </button>
</div>
<br>
<br>
<div align="center" id="help-button">
  <input type="button" class="button1" name="help-button" value="Help">
</div>

<footer> 

</footer>
