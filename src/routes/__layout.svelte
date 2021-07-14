<svelte:head>
	<title>Svelte Kit Example</title>
</svelte:head>

<nav>
	<a href=".">Home</a>
	<a href="about">About</a>
	<a href="settings">Settings</a>
</nav>

<br style ="line-height:3;">

<slot></slot>

<style>
/* vertical  */    
/*    nav {
        list-style-type: none;
        margin: 0;
        padding: 0;
        width: 90px;
        background-color: #f1f1f1;
        border: 1px solid #555;
    }
      
    a {
        display: block;
        color: #000;
        padding: 8px 16px;
        text-decoration: none;
        text-align: center;
        border-bottom: 1px solid #555;
    }
      */
      /* Change the link color on hover */
/*      a:hover {
        background-color: #555;
        color: white;
    }

    a:last-child {
        border-bottom: none;
    }
*/

nav {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
  /* fixed top, need to add <br> to content pages  */
  position: fixed;
  top: 0;
  width: 100%; 
}


a {
  display: block;
  float: left;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  border-right: 1px solid #bbb;
}

a:last-child {
  border-right: none;
}

/* Change the link color to #111 (black) on hover */
a:hover {
  background-color: #111;
}


</style>