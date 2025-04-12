// pages/index.jsx
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { useState } from "react";

export default function Home() {
  const [isSubscribed, setIsSubscribed] = useState(false);

  return (
    <main className="min-h-screen bg-black text-white p-4 space-y-10">
      <section className="text-center space-y-4">
        <h1 className="text-4xl font-bold">Exclusive +18 Content</h1>
        <p className="text-lg">Private photos and videos just for you.</p>
      </section>

      <section>
        <h2 className="text-2xl mb-4">Gallery</h2>
        <div className="grid grid-cols-2 md:grid-cols-4 gap-4">
          {[1, 2, 3, 4].map((id) => (
            <Card key={id}>
              <CardContent className="p-0">
                <img
                  src={`/media/preview${id}.jpg`}
                  alt="Exclusive content"
                  className="w-full h-48 object-cover rounded"
                />
              </CardContent>
            </Card>
          ))}
        </div>
      </section>

      <section className="text-center space-y-4">
        <h2 className="text-2xl">Subscribe for Full Access</h2>
        <p>Secure payment via PayPal</p>
        <form
          action="https://www.paypal.com/donate"
          method="post"
          target="_blank"
        >
          <input type="hidden" name="business" value="leonelmuando60@gmail.com" />
          <input type="hidden" name="no_recurring" value="0" />
          <input type="hidden" name="item_name" value="Full access" />
          <input type="hidden" name="currency_code" value="USD" />
          <Button type="submit">Subscribe Now</Button>
        </form>
      </section>

      <section className="text-center mt-10">
        <h2 className="text-2xl">Support</h2>
        <a
          href="https://t.me/Chillsexy9"
          className="text-blue-400 underline"
          target="_blank"
        >
          Contact us on Telegram (@Chillsexy9)
        </a>
      </section>
    </main>
  );
}
