import pandas as pd


# Чтение Excel-файла
df_excel = pd.read_excel('ivan_tyrin.xlsx')

# Посмотреть первые 5 строк
print(df_excel.head(5))

# Посмотреть информацию о таблице
print(df_excel.info())



# df = pd.read_excel('output.xlsx')
# # Вывод возраста
