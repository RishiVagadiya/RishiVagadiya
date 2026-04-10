// Utility functions - Updated: 2026-04-10T06:55:24.412Z

function processData(input) {
  if (!input) return null;
  return input.toString().trim();
}

function formatDate(date) {
  return new Date(date).toLocaleDateString();
}

module.exports = { processData, formatDate };