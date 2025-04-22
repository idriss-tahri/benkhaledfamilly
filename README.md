function MainComponent() {
  return (
    <div className="min-h-screen bg-black text-[#8b0000] font-bold pt-20">
      <div className="max-w-4xl mx-auto px-6 py-12">
        <h1 className="text-4xl mb-8 text-center">قوانين السيرفر</h1>
        
        <div className="space-y-8">
          <div className="bg-[#1a0000] rounded-lg p-6">
            <h2 className="text-2xl mb-4">القواعد العامة</h2>
            <ul className="space-y-4">
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>احترام جميع الأعضاء وعدم استخدام لغة مسيئة</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>يمنع منعاً باتاً نشر المحتوى غير اللائق</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>عدم استخدام أي برامج غش أو تهكير</span>
              </li>
            </ul>
          </div>

          <div className="bg-[#1a0000] rounded-lg p-6">
            <h2 className="text-2xl mb-4">قواعد اللعب</h2>
            <ul className="space-y-4">
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>الالتزام بدور الشخصية المختارة</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>عدم استغلال الثغرات في اللعبة</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>احترام قرارات المشرفين</span>
              </li>
            </ul>
          </div>

          <div className="bg-[#1a0000] rounded-lg p-6">
            <h2 className="text-2xl mb-4">العقوبات</h2>
            <ul className="space-y-4">
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>تحذير أول للمخالفات البسيطة</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>حظر مؤقت للمخالفات المتكررة</span>
              </li>
              <li className="flex items-start">
                <i className="fas fa-circle text-xs mt-2 ml-2"></i>
                <span>حظر دائم للمخالفات الجسيمة</span>
              </li>
            </ul>
          </div>
        </div>

        <div className="mt-12 text-center">
          <p className="text-xl mb-6">بالموافقة على هذه القواعد، يمكنك الانضمام إلى مجتمعنا</p>
          <button className="bg-[#8b0000] text-white px-8 py-3 rounded-lg text-xl hover:bg-[#660000] transition">
            موافق على القواعد
          </button>
        </div>
      </div>
    </div>
  );
}


