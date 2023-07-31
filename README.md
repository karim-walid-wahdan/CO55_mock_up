
# CO55_mock_up

This repository contains a site mock-up for a business coworking space based on [this design](https://xd.adobe.com/view/d92a7930-0566-41e9-b8b5-d926ef670606-8c79/) using Bootstrap v5 and JavaScript.

## Installation

To clone this repository, run:

```
git clone https://github.com/karim-walid-wahdan/CO55_mock_up.git
```

## Usage

Open the `index.html` file in your web browser to view the site mock-up.

## Code Samples

Here are some code samples from within the repository:

1. The navigation bar HTML code in `index.html`:

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">CO55</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
      aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">About</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
            aria-expanded="false">
            Services
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Meeting Rooms</a></li>
            <li><a class="dropdown-item" href="#">Event Spaces</a></li>
            <li><a class="dropdown-item" href="#">Coworking Spaces</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
```

2. The custom styles for the homepage in `assets/css/style.css`:

```css
/* Homepage */
#home {
  height: calc(100vh - 80px);
  background-image: url('../assets/images/hero.jpg');
  background-size: cover;
  background-position: center;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  text-align: center;
}

#home h1 {
  font-size: 4rem;
  color: #fff;
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
  margin-bottom: 2rem;
}

#home p {
  font-size: 1.5rem;
  color: #fff;
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
  margin-bottom: 2rem;
}

#home .btn-primary {
  background-color: #1d3557;
  border-color: #1d3557;
  font-size: 1.2rem;
  padding: 0.8rem 2rem;
  border-radius: 0;
  margin-top: 2rem;
}

#home .btn-primary:hover {
  background-color: #0b2239;
  border-color: #0b2239;
}
```

3. The JavaScript code for the "Book Now" button in `assets/js/script.js`:

```js
const bookNowBtn = document.querySelector('.book-now-btn');

bookNowBtn.addEventListener('click', () => {
  alert('Booking feature is not available in this mock-up!');
});
```

## Contributing

Contributions to this repository are not currently accepted.

