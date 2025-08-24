# Movie Filter App 🎬

A responsive React application that displays a collection of movies with category-based filtering functionality. Users can browse through movies and filter them by genres like Action, Thriller, Animation, Horror, Drama, and Sci-Fi.

<img width="1919" height="971" alt="Screenshot 2025-08-25 012452" src="https://github.com/user-attachments/assets/f4d1e75a-645b-4b8a-bb5d-5dcce9cf00d8" />
<img width="1918" height="966" alt="Screenshot 2025-08-25 012505" src="https://github.com/user-attachments/assets/f8003122-0a54-4ccb-80f6-ef16e68cbc41" />
<img width="1916" height="966" alt="Screenshot 2025-08-25 012525" src="https://github.com/user-attachments/assets/de600a65-0a2a-43cb-8b22-471e2b67cf1b" />


## Features ✨

- **Movie Gallery**: Display movies with poster images, titles, and release dates
- **Category Filtering**: Filter movies by genre (Action, Thriller, Animation, Horror, Drama, Sci-Fi)
- **Responsive Design**: Clean, centered layout that works across different screen sizes
- **Hover Effects**: Interactive hover animations on movie posters
- **Modern UI**: Dark theme with colorful filter buttons

## Technologies Used 🛠️

- **React 18** - Frontend framework
- **JavaScript (ES6+)** - Programming language
- **CSS3** - Styling with custom hover effects
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Build tool and development server

## Project Structure 📁

```
movie-filter-app/
├── src/
│   ├── App.jsx          # Main app component
│   ├── Movies.jsx       # Movie display and filtering logic
│   ├── data.js          # Movie data array
│   ├── index.css        # Global styles and custom CSS
│   └── main.jsx         # App entry point
├── public/
└── README.md
```

## Installation & Setup 🚀

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/movie-filter-app.git
   cd movie-filter-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## Usage 💡

1. **Browse Movies**: Scroll through the movie gallery to see all available movies
2. **Filter by Category**: Click on any category button (Action, Thriller, Animation, etc.) to filter movies
3. **View All Movies**: Click the "All" button to reset filters and show all movies
4. **Hover Effects**: Hover over movie posters to see the zoom animation effect

## Movie Data Structure 📊

Each movie object contains:
```javascript
{
  id: number,
  title: string,
  release_date: string,
  backdrop_path: string,
  poster_path: string,
  category: string
}
```

## Available Categories 🎭

- **All** - Shows all movies
- **Action** - Action and superhero movies
- **Thriller** - Suspense and thriller films
- **Animation** - Animated movies and cartoons
- **Horror** - Horror and scary movies
- **Drama** - Dramatic films
- **Sci-Fi** - Science fiction movies

## Customization 🎨

### Adding New Movies
Edit the `src/data.js` file to add new movies:
```javascript
{
  id: 123456,
  title: "New Movie",
  release_date: "2024-12-01",
  backdrop_path: "background-image-url",
  poster_path: "poster-image-url",
  category: "Action"
}
```

### Adding New Categories
1. Add movies with the new category in `data.js`
2. Add a new filter button in `Movies.jsx`:
```jsx
<button
  onClick={() => filterByCategory("NewCategory")}
  type="button"
  className="btn btn-outline-primary mx-3"
>
  New Category
</button>
```

### Styling
- Global styles: `src/index.css`
- Component-specific styling: Inline styles in `Movies.jsx`
- Tailwind utilities: Used throughout components

## Browser Support 🌐

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing 🤝

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

## Future Enhancements 🔮

- [ ] Search functionality
- [ ] Movie details modal
- [ ] Sorting options (by date, title, etc.)
- [ ] Pagination for large movie collections
- [ ] API integration for real-time movie data
- [ ] User favorites/watchlist
- [ ] Movie ratings and reviews

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Movie posters and images from various sources
- Icons and styling inspiration from modern web design trends
- React community for excellent documentation and resources

---

**Made with ❤️ by Aman-Bam**

*Feel free to star ⭐ this repository if you found it helpful!*
