# MyAndroidToolsWebsite
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:"Quicksand",sans-serif;
  
}

body{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background: #111;
  
}

.container
{
  position: relative;
  width: 800px;
  height: 500px;
  background: #222;
}

.container .clip
{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  transition: 0.5%;
  
}

.container .clip.clip1
{
  background: url(https://lh3.googleusercontent.com/fife/ABSRlIoUPlZpSV9wXgEw2k9BHVXlDD4diTpKAa3nOHY3Uwbff0aFy_cQOAszLSr2IA67dV7-xZTNlVuY7C7klwN2UsECnSlfBZ6gBaOdcuLeeOJQsi7a4k4gs9difvWIb-B0vsEhii8ZhV7kLbjUZKXajj3Nff_RQa8QL7UdfppQJ5_GlJZYX6qZrIqDXFZhtpDJoHRdXQJVMJFB3exJ2OBssmFVVX11dPPFLjkTvy2JPKN1cMfVtSEFI-Tp9PrA4dp9ILmKKRrlnPfKLhJGUffJNdoSmd_2Bb5eqU9Wr_25uMlYncVp2FZjZuHhfh3rxECmVhbE5kctnyH95DzqyF5qr2q0qIlOL26p-74jX_uLLSqcapbq6MFit1Q9AIwoJtCZwMuwKZMRZOlCvSmoM7uQ1pBFOdXAidc43-XsA5_XJoFyw-a5YJHYzD1UKNxSJRov3kZEOvTFKn3NAVbRPZ_3ZETgKQFNQeFgSUi8hhwH9K2tUWtP-lJibQBGzE4DsyYNbSeBCZgoFlBjEMt2n2uDCwHD-F13Bb3UlgCy33zosPZ2rmNczF3pmLFeMr7c2z0gQ9p38zmqUWp47ww5nXaUrdazJXjgX7U4OZjUxSYvOJmNmmToZ6DAPAy0bD8z-jpIbL9I0RiqVMTu5igpfFdoMmdIOgm3fBqKShxAoBZdIxCcOE5nW82XIduiC2hi3zhAsjlx_tMV1R6e8eo4Ni8Rn7Kltk6Hb46DNQ=w348-h260-p-k-nu-ft);
  background-size: cover;
  clip-path: polygon(0 0, 41% 0, 16% 100%, 0% 100%);
  
}

.container .clip.clip2
{
  background: url(https://lh3.googleusercontent.com/fife/ABSRlIqMrUO7xKs1X0lDT5BEAEYWYb_kutWBDncW_G15XaHwcCxJheWFijmF5qE8rObIro6iazxzQxXxxfjKzBrBv-2jDcXImbpiRLyK4JXpCiVbNCoQl7v54VN39N0ieDkeOL0FDepibEPQIE_eHc0mgEFL6mQ_WKlbd_pgt6mZj2wS4E0h57XkHi3FYFrOS5g9i7TktuRBDadw9NCKI--bmM2lKgTWvOk6Jh-gVlHO3OJSPqIL5qEfu_4AtQVHpqOY1f8xqNgcJ2OHQ_uvOnBr1PODmlmxdffEflgQKCJ3pse0lyYbEdDQYr96_WqYI1f8HUm5myCSnxFd4Ff8aB3sGuQ-KFtU1gIGZWzScLcmMzUCBKTWDvK1-EWlxv64kPRZtJmSmUbdaEsuo4s9GCoWHZPSOyvhhZcyPpE9-uiGXnLZWGupM3NGlumkkQvIAjjiIGvE5JlbL29ZP9UoA-55cZ9PmcxzLzr-Pcqqv99KIi5EbVncZKD9GZtoLme3sv7-4v0Jgit3N7MtRHBSTpvYw66dLMf8dBt60jTww6_drTQLLF6-dTZakttrOoVYUhLB9jWIMN7Sxkbo9cG2MnBvOK0YarlayDcIbbLnafs5AmOdG1a6_J9D2Hy459bdCc4OQZA0ynHhO6LlIvGUISY3HMN8nGQ29bdrWnUMaCIN7UIQfETj2TzHoDn2lzms6lAX4sjGx5o-F40n7C5_bkLLCOWdWdrA68D1rg=w348-h260-p-k-nu-ft);
  background-size: cover;
  clip-path: polygon(100% 0, 41% 0, 16% 100%, 51% 100%);
}

.container .clip.clip3
{
  background: url(https://images.pexels.com/photos/177598/pexels-photo-177598.jpeg?cs=srgb&dl=pexels-markus-spiske-177598.jpg&fm=jpg);
  background-size: cover;
  clip-path: polygon(100% 0, 100%  0, 100% 100%, 51% 100%);
  
}

.container:hover .clip
{
  clip-path:  polygon(100% 0, 100% 0, 100% 100%, 100% 100%);
}


.container .clip:hover
{
 
  clip-path: polygon(100% 0, 0 0, 0 100%, 100% 100%);
  
}

.container .clip.content
{
  position: absolute;
  bottom: 0;
  left: 0;
  width: 70%;
  padding: 20px;
  opacity: 0;
  background: #FFF;
  transition: 0.5%;
  
}

.container .clip:hover.content
{
  bottom: 0;
  opacity: 1%;
}
