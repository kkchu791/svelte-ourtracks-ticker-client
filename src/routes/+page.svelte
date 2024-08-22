<script lang="ts">
	import profile from '../lib/images/1200px-Art_of_Bookbinding_p098_Registered_Cutting_Machine.png';
</script>

<div class='page'>
  <div class='card'>
    <div class='avatar'>
      <div class='profile-photo'>
        <img class="image" alt="profile-photo" src={profile} />
      </div>
    </div>

    <div class='right'>
      <div class='card-content'>
        <div class='task'>
          Kirk C is laying the tracks for Entrepreneurship by Researching a new Desk
        </div>
        <div class='timestamp'>
          3 minutes ago
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .hello {
    color: orange;
  }
  .page {
      background: pink;
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
  }
  .card {
    width: 1250px;
    height: 550px;
    border: 5px solid black;
    border-radius: 10px;
    display: flex;
    flex-direction: row;
  }
  .avatar {
    display: flex;
    justify-content: center;
    align-items: center;
    border: 1px solid orange;
    width: 100%;
  }
  .profile-photo {
    height: 50%;
    width: 50%;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .right {
    border: 1px solid green;
    background: peach;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center
  }
  .card-content {
    width: 90%;
    display:flex;
    flex-direction: column;
    align-content: space-between;
  }
  .task{
    font-size: 36px;
    align-self: flex-start;
  }
  .timestamp {
    align-self: flex-end;
    width: 100px;
  }
  .image {
    width: 100%;
    height: 100%;
  }
</style>

