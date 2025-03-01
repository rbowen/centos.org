---
title: CentOS Project
layout: default
---
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script type="text/javascript" >
$(document).ready(function () {
        $('#divRss').FeedEk({
            FeedUrl: 'https://www.centos.org/assets/planet.rss',
            DescCharacterLimit:100,
            ShowPubDate: false,
            MaxCount: 4
        });
});
</script>

<div class="row">
  <div class="jumbotron col-md-12">
    <h1>The CentOS Project</h1>
    <p>The CentOS Project is a community-driven free software effort focused on delivering a robust open source ecosystem. For users, we offer a consistent manageable platform that suits a wide variety of deployments. For open source communities, we offer a solid, predictable base to build upon, along with extensive resources to build, test, release, and maintain their code.</p>
    <p> We're also expanding the availability of CentOS images across a number of vendors, providing official images for <a href="https://aws.amazon.com/marketplace/pp/B00O7WM7QW">Amazon</a>, Google, and more. For self-hosted cloud, we also provide a <a href="https://cloud.centos.org/centos/7/images/CentOS-7-x86_64-GenericCloud.qcow2.xz">generic cloud-init enabled image.</a></p>
    <p>For more information about updates and improvements in CentOS 7, please check out the <a href="https://wiki.centos.org/Manuals/ReleaseNotes/CentOS7">release notes</a> or the <a href="https://lists.centos.org/pipermail/centos-announce/2018-May/022829.html">release announcement</a> in the mailing list archive.</p>
    <div class="downloadbutton"><a href="/download/">Get CentOS Now</a></div>
  </div>
</div>
<div class="row">
  <div class="col-sm-4">
    <h2 class="text-center">Around CentOS</h2>
    <div id="divRss">
    </div>
  </div>
  <div class="col-sm-4">
    <h2 class="text-center">News & Events</h2>


<!-- Social Media Icons -->
<!-- See extra.scss for supporting CSS -->
 <a href="https://www.facebook.com/groups/centosproject/"><i class="fa fa-facebook"></i></a>
 <a href="https://twitter.com/centosproject"><i class="fa fa-twitter"></i></a>
 <a href="https://google.com/+CentOS"><i class="fa fa-google-plus"></i></a>
 <a href="https://youtube.com/TheCentOSProject"><i class="fa fa-youtube"></i></a>
 <a href="https://www.linkedin.com/groups/22405"><i class="fa fa-linkedin"></i></a>
 <a href="https://www.reddit.com/r/CentOS/"><i class="fa fa-reddit"></i></a>
<!-- /Social Media Icons -->

<br />
<br />

  
     <div class="media">
      <a class="pull-left" href="#">
        <img class="media-object img-rounded" src="/images/centoslogo-32.png" width="32" alt="..."></a>
      <div class="media-body">
        <h4 class="media-heading">CentOS Dojo @ FOSDEM</h4>
        <p><strong>February 1, 2019</strong>: We will be hosting a <a href="https://wiki.centos.org/Events/Dojo/Brussels2019">Dojo on the day before FOSDEM</a>, in Brussels. The schedule and registration are now available. See you in Brussels!
        </p>
      </div>
    </div> 

  
    <div class="media">
      <a class="pull-left" href="#">
        <img class="media-object img-rounded" src="/images/centoslogo-32.png" width="32" alt="..."></a>
      <div class="media-body">
        <h4 class="media-heading">CentOS Dojo @ CERN</h4>
        <p><strong>October 19th, 2018</strong>: We held our annual
        CentOS Dojo, and SIG Gathering Day at
        <a href="https://cern.ch/centos/">CERN, in Meyrin, Switzerland</a>. The video recordings are available on the <a href="https://indico.cern.ch/event/727150/timetable/#20181019">event agenda page</a>.
        </p>
      </div>
    </div> 


  </div>

  <div class="col-sm-4">
    <h2 class="text-center">Sponsorship</h2>
    <p>CentOS would not be possible without the support of our sponsors. We would like to thank the following product/service for being a CentOS sponsor:</p>
    <div class="cycle-slideshow" data-cycle-random="true" data-cycle-timeout="3000" data-cycle-fx="fade" data-cycle-center-horz="true" data-cycle-center-vert="true" data-cycle-loader="wait" data-cycle-progressive="#images" data-cycle-slides="&gt; a" data-cycle-pause-on-hover="true">

        {% for sponsor in site.data.sponsors %}
          <a href="{{ sponsor.url }}" rel="nofollow"><img class="img-rounded" src="{{ sponsor.img }}"></a>
        {% endfor %}

    </div>
    <br> 
    <p><a href="/sponsors/">If you value our work, please consider becoming a sponsor!</a></p>



  </div>
