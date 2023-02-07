
<div>
  <button>+</button>
</div>

<style>
  div {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 40px;
    border-top: 2px solid var(--light-gray);
    background-color: var(--gray-2);
    position: sticky;
    bottom: 0;
  }

  button {
    width: 60px;
    height: 60px;
    border: none;
    background-color: var(--light-gray);
    color: var(--gray-2);
    border-radius: 50%;
    font-size: 2.5rem;
    font-weight: bold;
    position: relative;
    z-index: 1;
    top: -20px;
    transition: all 1s ease-in-out;
  }

  button:focus {
    outline: none;
  }

  button:active {
    transform: scale(0.5);
  }
</style>