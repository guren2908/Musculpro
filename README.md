<style>
  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: translateY(30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .card {
    background-color: #1f1f2e;
    border-radius: 20px;
    padding: 20px;
    width: 300px;
    box-shadow: 0 0 15px rgba(0, 191, 255, 0.2);
    text-align: center;
    animation: fadeIn 1s ease forwards;
    opacity: 0;  /* Garantiza que las tarjetas estén ocultas inicialmente */
  }

  .card:nth-child(1) {
    animation-delay: 0.2s;
  }

  .card:nth-child(2) {
    animation-delay: 0.4s;
  }

  .card:nth-child(3) {
    animation-delay: 0.6s;
  }

  .card:nth-child(4) {
    animation-delay: 0.8s;
  }
</style>
