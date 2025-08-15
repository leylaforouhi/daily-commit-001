
def daily_message():
    from datetime import datetime
    today = datetime.now().strftime("%Y-%m-%d")
    return f"Hello GitHub! Today is {today}"

if __name__ == "__main__":
    print(daily_message())
