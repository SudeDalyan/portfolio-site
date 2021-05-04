<template>
  <div>
    <div class="row">
      <div class="col-md-6">

        <div class="row skills-content">
          <div class="col-sm-6">
            <div class="card">
              <div class="card-body">
                <img src="../assets/languages.png"><br/><br/>
                <h5 class="card-title">A Good Translator</h5>
              </div>
            </div>
          </div>
          <div class="col-sm-6" style="margin-bottom:30px">
            <div class="card" style="margin-top:30px">
              <div class="card-body">
               <img src="../assets/conversation.png"><br/><br/>
                <h5 class="card-title">A Good Listener</h5>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card">
              <div class="card-body">
                <img src="../assets/document.png"><br/><br/>
                <h5 class="card-title">A Good Writer</h5>
              </div>
            </div>
          </div>
          <div class="col-sm-6">
            <div class="card" style="margin-top:30px">
              <div class="card-body">
                <img src="../assets/books.png"><br/><br/>
                <h5 class="card-title">A Good Library</h5>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="col-md-6 skills-headers">
        <div class="skills-head">
          <h1 style="font-weight: 600;">What My Writing</h1><br />
          <h3 style="font-weight: 600;">Skills Included</h3>
        </div>
        <p>A writer is a person who uses written words in different styles and techniques to communicate ideas. Writers
          produce different forms of literary art and creative writing such as novels, short stories, books, poetry,
          plays, screenplays, teleplays, songs, and essays as well as other reports and news articles that may be of
          interest to the public. Writers' texts are published across a range of media.</p>
        <div class="skills-skills">
          <p>FocusWriter</p>
          <div class="container">
            <div class="skill css">80%</div>
          </div>

          <p>WriteWayPro</p>
          <div class="container">
            <div class="skill js">90%</div>
          </div>

          <p>OpenOffice</p>
          <div class="container">
            <div class="skill php">75%</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'Skills',
    props: {
      msg: String
    }
  }
</script>