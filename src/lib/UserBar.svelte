<div class="user-bar">
  <div class="user-bar__name">
    <span>John Doe</span>
  </div>

  <div class="user-bar__avatar">
    <img
      src="https://www.gravatar.com/avatar/00000000000000000000000000000000"
      alt="Avatar"
    />
  </div>
</div>

<style>
  .user-bar {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1rem 2rem;
    background-color: var(--gray-2);
    overflow: hidden;
  }

  .user-bar__avatar {
    width: 40px;
    height: 40px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0 0rem;
  }

  .user-bar__avatar img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }

  .user-bar__name {
    font-size: 1.5rem;
    font-weight: bold;
  }

  .user-bar__name span {
    color: var(--light-gray);
  }
</style>
