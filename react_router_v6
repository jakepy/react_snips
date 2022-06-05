import React from 'react'
import {
    BrowserRouter as Router,
    Routes,
    Route
  } from 'react-router-dom'

const App = () => {
  return (
    <Router>
        <Layout>
            <Routes>
                <Route path="/" element={<Notes />} exact/>
                <Route path="/:id" element={<Note />}/>
            </Routes>
        </Layout>
    </Router>
  )
}

export default App
