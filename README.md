import yfinance as yf

# Descargar datos históricos de las acciones de Tesla
tesla = yf.Ticker('TSLA')
tesla_data = tesla.history(period="1y")  # Datos de 1 año

# Mostrar los primeros 5 registros
tesla_data.head()
