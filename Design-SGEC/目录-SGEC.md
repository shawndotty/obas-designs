<grid filter="blur(10px)" drag="100 100" drop="0 0" class="fullImage">
![[bg.png]]
</grid>

<grid drag="60 80" drop="20 10" style="margin-left: 40px; margin-top: 40px;" class="bg-with-back-color">

</grid>

<grid class="content bg-with-front-color" drag="60 80" drop="20 10" pad="40px 60px"   align="left"   style="z-index: 999;" >
<grid class="bg-with-back-color" drag="2 20" drop="0 5"></grid>
<% content %>
</grid>