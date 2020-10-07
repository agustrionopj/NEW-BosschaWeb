---
resources:
    - src: carousel/1.jpg
      name: slide
      title:  
    - src: carousel/2.jpg
      name: slide 
      title:   
    - src: carousel/3.jpg
      name: slide 
      title: 
    - src: carousel/4.jpg
      album: astro 
      title: 
    # - src: carousel/1.png
    #   name: slide 
    #   title:
#       - src: carousel/2b.jpg
#       name: astro 
#       title:
#       - src: carousel/3b.jpg
#       name: astro 
#       title:
#       - src: carousel/4.png
#       name: astro 
#       title:
#       - src: carousel/5b.jpg
#       name: astro 
#       title:
    # - src: carousel/5.jpg
    #   name: slide 
    #   title: slide 5
---


### <i class="fas fa-meteor"></i> Astrofotografi
***
<!-- {{<carousel2 album="astro">}} -->

<style>
.thumbnail {
  /* width: 450px; */
	width: auto;
	height: 350px;
	overflow: hidden;
}
img {
	width: 100%;
	height: 100%;
	object-fit: cover;
}
</style>
<script>
	$('[data-fancybox]').fancybox({
		protect: true
	});
</script>

<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval=1750>
	<!-- <ol class="carousel-indicators">
		<li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
		<li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
		<li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
	</ol> -->
	<!--  -------------------------------------  -->
	<!-- display images dalam carousel -->
	<!-- -------------------------------------- -->
	<div class="carousel-inner">
		<div class="carousel-item active">
			<a href="astro/1.png" data-fancybox="astro" data-options='{"caption": "Kenampakan Matahari pada panjang gelombang Ca II K <br> Observer: Muhammad Yusuf"}'>
		 		<div class="thumbnail"> 
	  				<img src="astro/1.png" class="d-block w-100" alt="...">
				</div>
      			</a>
		</div>
		<div class="carousel-item">
			<a href="astro/2.jpg" data-fancybox="astro">
				<div class="thumbnail">
					<img src="astro/2.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
		<div class="carousel-item">
			<a href="astro/3.jpg" data-fancybox="astro">
				<div class="thumbnail">
					<img src="astro/3.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
	</div>
	<a class="carousel-control-prev" 				href="#carouselExampleIndicators" role="button" 		data-slide="prev">
		<span class="carousel-control-prev-icon" aria-hidden="true"></span>
		<span class="sr-only">Previous</span>
	</a>
	<a class="carousel-control-next" 				href="#carouselExampleIndicators" role="button" 		data-slide="next">
		<span class="carousel-control-next-icon" aria-hidden="true"></span>
		<span class="sr-only">Next</span>
	</a>
</div>

### <i class="fas fa-meteor"></i> Astro Day in School
***
<!-- ----------------------------------------------------
astroday album
---------------------------------------------------- -->
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval=1750>
	<!-- <ol class="carousel-indicators">
		<li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
		<li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
		<li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
	</ol> -->
	<!--  -------------------------------------  -->
	<!-- display images dalam carousel -->
	<!-- -------------------------------------- -->
	<div class="carousel-inner">
		<div class="carousel-item active">
			<a href="astroday/1.jpg" data-fancybox="astroday" data-options='{"caption": ""}'>
		 		<div class="thumbnail"> 
	  				<img src="astroday/1.jpg" class="d-block w-100" alt="...">
				</div>
      			</a>
		</div>
		<div class="carousel-item">
			<a href="astroday/2.jpg" data-fancybox="astroday">
				<div class="thumbnail">
					<img src="astroday/2.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
		<div class="carousel-item">
			<a href="astroday/3.jpg" data-fancybox="astroday">
				<div class="thumbnail">
					<img src="astroday/3.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
		<div class="carousel-item">
			<a href="astroday/4.jpg" data-fancybox="astroday">
				<div class="thumbnail">
					<img src="astroday/4.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
		<div class="carousel-item">
			<a href="astroday/5.jpg" data-fancybox="astroday">
				<div class="thumbnail">
					<img src="astroday/5.jpg" class="d-block w-100" alt="...">
				</div>
			</a>
		</div>
	</div>
	<a class="carousel-control-prev" 				href="#carouselExampleIndicators" role="button" 		data-slide="prev">
		<span class="carousel-control-prev-icon" aria-hidden="true"></span>
		<span class="sr-only">Previous</span>
	</a>
	<a class="carousel-control-next" 				href="#carouselExampleIndicators" role="button" 		data-slide="next">
		<span class="carousel-control-next-icon" aria-hidden="true"></span>
		<span class="sr-only">Next</span>
	</a>
</div>
<!-- 
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel" data-interval=1750>
	<div class="carousel-inner">
		<div class="carousel-item active">
			<a href="/.jpg" data-fancybox="" data-options='{"caption": ""}'>
		 		<div class="thumbnail"> 
	  				<img src="/.jpg" class="d-block w-100" alt="...">
				</div>
      			</a>
		</div>
		<div class="carousel-item">
			<a href="/.jpg" data-fancybox="" data-options='{"caption": ""}'>
		 		<div class="thumbnail"> 
	  				<img src="/.jpg" class="d-block w-100" alt="...">
				</div>
      			</a>
		</div>
	</div>
	<a class="carousel-control-prev" 				href="#carouselExampleIndicators" role="button" 		data-slide="prev">
		<span class="carousel-control-prev-icon" aria-hidden="true"></span>
		<span class="sr-only">Previous</span>
	</a>
	<a class="carousel-control-next" 				href="#carouselExampleIndicators" role="button" 		data-slide="next">
		<span class="carousel-control-next-icon" aria-hidden="true"></span>
		<span class="sr-only">Next</span>
	</a>
</div>
 -->