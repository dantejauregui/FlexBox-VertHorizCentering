# FlexBox-VertHorizCentering in signIn.html

Just adding in the parent tag container this flexbox css code:

.bgBoxParent{
			display: flex;
			align-items: center;
 			justify-content: center;
}

And Son container will center itself, also should check if a upper "grandfather" container has height: 100%, in my case when I was using Bootstrap3 I have a (DIV with class="row " that was limiting the height) so I add here another class called "bgRow" modifying CSS like this:

.bgRow{
				height: 100vh;
}

So with that was enough to do vert and horiz centering
