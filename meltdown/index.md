<style>
  .button1 {
    background-color: #F8F9F9;
    color: #2C0735;
    border: 2px solid #D11149;
    font-size: 16px;
    border-radius: 14px;
    padding: 10px 24px;
    cursor: pointer;
    transition: all 0.3s ease;
    }
  .button1:hover {
    color: #F8F9F9;
    background-color: #7C19DD;
    border-color: #7C19DD;
    }
  .button1:active {
    color: #F8F9F9;
    background-color: #C04CFD;
    border-color: #C04CFD;
    }
  .button1:focus {
    outline: none;
    box-shadow: 0 0 0 5px #C04CFD;
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
  # Meltdown
</div>         
        
<div id="meltdown_pic" align="center">
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
