**Riksdagen is an AI that generates photorealistic portraits of Swedish members of parliament. It is a custom machine learning model trained on about 1400 press photos of all Swedish members of parliament from 1992-2018.**

The process has imprinted the model with detailed visual information on the faces of power in Sweden during this period. As the generated images of the machine are based on properties it has learnt from the material, the output becomes a statistically accurate representation, prediction and reflection on who we choose to govern us.

<div id="ytplayer"></div>

<script>
  // Load the IFrame Player API code asynchronously.
  var tag = document.createElement('script');
  tag.src = "https://www.youtube.com/player_api";
  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

  // Replace the 'ytplayer' element with an <iframe> and
  // YouTube player after the API code downloads.
  var player;
  function onYouTubePlayerAPIReady() {
    player = new YT.Player('ytplayer', {
      height: '360',
      width: '640',
      videoId: 'ZZek1ozIV7k'
      autoplay: '1'
      modestbranding: '1'
      origin: 'github.io'
    });
  }
</script>

 <iframe id="ytplayer" type="text/html" width="640" height="360"
  src="https://www.youtube.com/embed/M7lc1UVf-VE?autoplay=1&origin=http://example.com"
  frameborder="0"></iframe>
  
### Physical outcomes

The work is intended to be shown as a series of 349 framed portraits on a wall, placed in the same formation as the seating in the Swedish parliament chamber plenissalen. In front of the wall, a screen showing a latent walk video of generated parliament members turning into new parliament members.

The work is also intended to be published in a book (“De 349” / “The 349”) with a print run of 349 copies, each with 349 generated members of parliament. (349 is the number of members of the Swedish parliament.)

### Software architecture

The software architecture of this work is based on AI research by Karras, T. et.al. (2019)[^1]. 


[^1]: Karras, T., Laine, S., Aittala, M., Hellsten, J., Lehtinen, J., & Aila, T. (2019). Analyzing and improving the image quality of StyleGAN.
