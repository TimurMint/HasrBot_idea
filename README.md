# HasrBot_idea

    return (
        <div className="flex flex-col items-center justify-center h-screen bg-blue-100">
            <h1 className="text-3xl font-bold">Счётчик кликов</h1>
            <p className="text-gray-700 text-lg">Ты нажал {count} раз</p>
            <button 
                className="mt-4 px-4 py-2 bg-blue-500 text-white rounded-lg hover:bg-blue-600"
                onClick={() => setCount(count + 1)}
            >
                Нажми меня
            </button>
        </div>
    );
}
